Archlinux PKGBUILD files for the treefrog framework
===================================================

This repository contains two PKGBUILD files for building packages of the [treefrog framework](http://www.treefrogframework.org) on [Archlinux](http://www.archlinux.org) systems. To build the packages, do the following:

```bash
$ git clone git@github.com:nsommer/treefrogpkgbuild.git
$ cd treefrogpkgbuild
$ cd framework
$ makepkg -s
$ sudo pacman -U <packagefilename>.pkg.tar.xz
$ cd ../tools
$ makepkg -s
$ sudo pacman -U <packagefilename>.pkg.tar.xz
```

You can also find the PKGBUILDs in the official [AUR](http://aur.archlinux.org):

* [treefrog-framework](https://aur.archlinux.org/packages/treefrog-framework/)
* [treefrog-tools](https://aur.archlinux.org/packages/treefrog-tools/)
