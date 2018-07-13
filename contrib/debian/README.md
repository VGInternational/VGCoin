
Debian
====================
This directory contains files used to package VGCoind/VGCoin-qt
for Debian-based Linux systems. If you compile VGCoind/VGCoin-qt yourself, there are some useful files here.

## VGCoin: URI support ##


VGCoin-qt.desktop  (Gnome / Open Desktop)
To install:

        sudo desktop-file-install VGCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your VGCoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

VGCoin-qt.protocol (KDE)

