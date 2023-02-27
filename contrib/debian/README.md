
Debian
====================
This directory contains files used to package sprycoind/sprycoin-qt
for Debian-based Linux systems. If you compile sprycoind/sprycoin-qt yourself, there are some useful files here.

## pivx: URI support ##


sprycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sprycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sprycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/sprycoin128.png` to `/usr/share/pixmaps`

sprycoin-qt.protocol (KDE)

