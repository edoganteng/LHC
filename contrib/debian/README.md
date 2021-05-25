
Debian
====================
This directory contains files used to package Lightcoind/Lightcoin-qt
for Debian-based Linux systems. If you compile Lightcoind/Lightcoin-qt yourself, there are some useful files here.

## Lightcoin: URI support ##


Lightcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Lightcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Lightcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/Lightcoin128.png` to `/usr/share/pixmaps`

Lightcoin-qt.protocol (KDE)

