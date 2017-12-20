
Debian
====================
This directory contains files used to package snxd/snx-qt
for Debian-based Linux systems. If you compile snxd/snx-qt yourself, there are some useful files here.

## snx: URI support ##


snx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install snx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your snxqt binary to `/usr/bin`
and the `../../share/pixmaps/snx128.png` to `/usr/share/pixmaps`

snx-qt.protocol (KDE)

