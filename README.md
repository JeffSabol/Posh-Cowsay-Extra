Posh-Cowsay - Cowsay for Windows Powershell
===========================================
A shell cannot be called civilised until it has a talking cow... with a santa hat and a friend cat.

     _______________________________
    < For POSH users with Unix envy >
     -------------------------------
          \  ^__^             
           \ (oo)\________    
             (__)\        )\/\
                  ||----w |   
                  ||     ||   
     _____
    < Yes >
     -----
      \     .-""-.
       \   /,..___\
        \ () {_____}
         \    ^__^
          \   (oo)\________
              (__)\        )\/\
                   ||----w |
                   ||     ||
                  

Based on Tony Monroe's original Unix terminal program cowsay:

http://www.nog.net/~tony/warez/cowsay-3.03.tar.gz

Usage
=====
> Catsay Hello World

> Santacowsay Ho ho ho

> Cowsay -b Borg

> Cowsay -d Dead

> Cowsay -g Greedy

> Cowsay -p Paranoid

> Cowsay -s Borg

> Cowsay -y Youthful

For examples see the built-in Powershell help:

    > get-help cowsay -examples

Install
=======
Posh-Cowsay is a single Powershell Module file with no dependencies. To install it:

1. Copy [cowsay.psm1](https://raw.github.com/kanej/posh-cowsay/master/cowsay.psm1) into a new folder called cowsay within your modules folder (C:\Users\\*UserName*\Documents\WindowsPowerShell\Modules\cowsay on Windows 7).

2. Open a new Powershell terminal and import the module

    > Import-Module cowsay

3. cowsay That was easy ... ish

TODO
====
1. Support the modes that the original cowsay supported e.g. XX for the cows eyes.
2. Support for arbitary whitespace (the -n option in cowsay).
3. A way of dealing with cow files or an equivalent.

Contributors
============

* John Kane
* Andrew Thomson

License
=======
Posh-Cowsay is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Posh-Cowsay is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
