% nyaa_modules(8)

# NAME
nyaa modules - module system for nyaa

# SYNOPSIS
nyaa m [l] [MODULE NAME]

# DESCRIPTION
nyaa modules is a module system that allows you to extend the capabilities of nyaa without modifying the main code and/or without forking it.

**l**
    List modules

# MODULE STRUCTURE
**We highly recommend looking at nyaa's module() function as there might be breaking changes**

Modules are named with the .nyaa extension. The modules should be written in a POSIX-compliant language (bash, zsh, sh etc.). Though it is possible to use other languages inside the module if you need so.

An example module structure;

```
#!/bin/sh
MODULE_NAME="test"
MODULE_VER="1.0"
MODULE_DESC="Example module"

main() {
    # Main functions reside here
}

help() {
    # Help resides here
}

version() { 
    # Version information resides here
}
```
Now lets break it down.

## VARIABLES
* MODULE_NAME: Name of your module. Will show this name on the list command.
* MODULE_VER: Version of your module. Will show this on list command.
* MODULE_DESC: Description of your module. Will show this on the list command.

## FUNCTIONS
* main: the main function of your module should reside here.
* help: help and related documentation should reside here. Will be run when the user runs `nyaa m <modulename> h`.
* version: version and license information should reside here. Will be run when the user runs `nyaa m <modulename> v`.


# AUTHOR
Written by Kreato.

# COPYRIGHT
nyaa is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

nyaa is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with nyaa.  If not, see <https://www.gnu.org/licenses/>.
