
Debian
====================
This directory contains files used to package revud/revu-qt
for Debian-based Linux systems. If you compile revud/revu-qt yourself, there are some useful files here.

## revu: URI support ##


revu-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install revu-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your revuqt binary to `/usr/bin`
and the `../../share/pixmaps/revu128.png` to `/usr/share/pixmaps`

revu-qt.protocol (KDE)

