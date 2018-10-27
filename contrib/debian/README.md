
Debian
====================
This directory contains files used to package mastercoind/mastercoin-qt
for Debian-based Linux systems. If you compile mastercoind/mastercoin-qt yourself, there are some useful files here.

## mastercoin: URI support ##


mastercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mastercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mastercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/mastercoin128.png` to `/usr/share/pixmaps`

mastercoin-qt.protocol (KDE)

