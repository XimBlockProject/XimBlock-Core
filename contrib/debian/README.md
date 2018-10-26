
Debian
====================
This directory contains files used to package ximblockd/ximblock-qt
for Debian-based Linux systems. If you compile ximblockd/ximblock-qt yourself, there are some useful files here.

## ximblock: URI support ##


ximblock-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ximblock-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ximblockqt binary to `/usr/bin`
and the `../../share/pixmaps/ximblock128.png` to `/usr/share/pixmaps`

ximblock-qt.protocol (KDE)

