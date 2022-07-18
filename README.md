# nyaa
`nyaa` is a package manager written in POSIX sh, mainly for use with Kreato Linux.
`nyaa` is heavily inspired by the `kiss` package manager.

# Installation
Installation is done by choosing to install the `nyaa` package manager on `nyaa-src`.

Alternatively, installation can be done on any Linux system by putting the `nyaa` file to PATH.
Please be warned that you will not have support in any way if you do this.

# FAQ

## Is this a meme? Why is the name `nyaa` chosen?
This is not a meme.
I spent too much on this project to be just a "meme".
The name was chosen because it is a original name (suprisingly nobody made a package manager named `nyaa`). 
Also it is a short name that is extremely fast to type (which is important for a package manager since you will use it a ton). 
The name also implies how much of a weeb i am.

## Why isn't there a Makefile unlike rest of your projects?
Because this isn't meant to be installed by your ordinary user. 
This package manager gets installed by `nyaastrap` and that will be the case. I may put a Makefile just for compiling the manpage though.

## Why does it output so many warnings and errors, instead of being log-free like most package managers?
I like debug outputs. It makes my job much easier, and for probably yours too if you encounter a issue. 
And this is my distro so my preferences come first (no hard feelings).

## Why did you code this project instead of using another package manager?
One of the main "feature"s of distro is it is "different". There is thousands of distros doing that.
Why should we? Why shouldn't we make a simple package manager for our distribution? 
Why should we make distro X that has no things different from other distributions other than some custom tools?
If i want to use `pacman` for example i'd just do a ArchISO like 90 million other people.
Also, I haven't found a package manager that is this simple, so simple that you can read the code and understand it in a hour which is a far cry from other package manager projects.

## Why is the repositories so small?
The repositories are being worked on. This was much harder than i thought it would so you'll have to wait for a while until theres enough packages for a nice system.

# License
Licensed under GPLv3, see LICENSE for details.
