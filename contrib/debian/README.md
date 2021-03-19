
Debian
====================
This directory contains files used to package btcnoded/btcnode-qt
for Debian-based Linux systems. If you compile btcnoded/btcnode-qt yourself, there are some useful files here.

## btcnode: URI support ##


btcnode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install btcnode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your btcnode-qt binary to `/usr/bin`
and the `../../share/pixmaps/btcnode128.png` to `/usr/share/pixmaps`

btcnode-qt.protocol (KDE)

