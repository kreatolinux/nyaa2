% nyaa(8)

# NAME
nyaa - package manager

# SYNOPSIS
**nyaa** [h] [b] [m] [s] [i] [I] [c] [r] [u] [U] [v] [PACKAGE] [-y] [-o] [-r] [ROOTFS]

# DESCRIPTION
Nyaa is a package manager written in POSIX sh. It is under 700> LOC and is meant to be used with Kreato Linux.
Nyaa uses simple build scripts called runfiles, similar to PKGBUILDs found in the pacman package manager.

**h**
    Output help

**b**
    build package

**m**
    Use modules, see nyaa_modules(8)

**s**
    search packages

**i**
    install binary package

**I**
    get info about a package

**c**
    chroot

**r** 
    remove package

**u**
    update repository

**U**
    upgrade packages

**v**
    print version

**-o**
    only build, dont install

**-r**
    Rootfs argument.

**-y**
    Auto-accept installation.

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
