
# What is this ?

A bunch of color schemes for Intellij-based IDEs, such as
[PyCharm](http://www.jetbrains.com/pycharm/) and
[CLion](https://www.jetbrains.com/clion/). These schemes were not created by me,
I merely ported them, because I wasn't happy with what I found online.

Here is the current list:

## Github

These scheme uses github syntax highlighting and actually applies them as github
does, instead of just copying color values and applying them arbitrarily to
source code. It takes however some liberties as Intellij's language parsers
often allows more control on what you can style.

## Solarized Light

Adapted from [Ethan Schoonover](http://ethanschoonover.com/solarized)


# Installation

Recent versions of Intellij IDEs use xml files with the extension `.icls`. These
files should be copied to the appropriate directory, depending on the IDE and
your platform.

## PyCharm

* macOS: `~/Library/Preferences/PyCharm${version}/colors/` 
* Linux: `~/.PyCharm40/config/color`
* Windows Vista, 7, 8, 10: `C:\Users\$USER\.PyCharm${version}\config\colors`
* Windows XP: `C:\Documents and Settings\$USER\.PyCharm${version}\config\colors`

## CLion

* macOS: `~/Library/Preferences/clion${version}/colors/` 
* Linux: `~/.clion${version}/config/color`
* Windows Vista, 7, 8, 10: `C:\Users\$USER\.clion${version}\config\colors`
* Windows XP: `C:\Documents and Settings\$USER\.clion${version}\config\colors`

