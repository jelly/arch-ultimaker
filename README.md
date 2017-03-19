# Ultimaker 3d printer software packaging for Arch Linux

Work in progress packaging of Cura, software for 3d printers. Currently segfaults due to a python-pyqt [bug](https://bugs.archlinux.org/task/53371).

## Repository

Add the following to your pacman.conf

```
[ultimaker]
SigLevel = Optional TrustAll
Server = https://pkgbuild.com/~jelle/ultimaker/
```
