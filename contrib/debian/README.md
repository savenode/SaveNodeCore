
Debian
====================
This directory contains files used to package savenoded/savenode-qt
for Debian-based Linux systems. If you compile savenoded/savenode-qt yourself, there are some useful files here.

## savenode: URI support ##


savenode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install savenode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your savenodeqt binary to `/usr/bin`
and the `../../share/pixmaps/savenode128.png` to `/usr/share/pixmaps`

savenode-qt.protocol (KDE)

