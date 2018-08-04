
Debian
====================
This directory contains files used to package botcoind/botcoin-qt
for Debian-based Linux systems. If you compile botcoind/botcoin-qt yourself, there are some useful files here.

## botcoin: URI support ##


botcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install botcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your botcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/botcoin128.png` to `/usr/share/pixmaps`

botcoin-qt.protocol (KDE)

