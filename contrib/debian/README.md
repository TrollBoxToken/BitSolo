
Debian
====================
This directory contains files used to package bitsolod/bitsolo-qt
for Debian-based Linux systems. If you compile bitsolod/bitsolo-qt yourself, there are some useful files here.

## bitsolo: URI support ##


bitsolo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitsolo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitsoloqt binary to `/usr/bin`
and the `../../share/pixmaps/bitsolo128.png` to `/usr/share/pixmaps`

bitsolo-qt.protocol (KDE)

