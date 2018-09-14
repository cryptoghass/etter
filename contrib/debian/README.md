
Debian
====================
This directory contains files used to package etterd/etter-qt
for Debian-based Linux systems. If you compile etterd/etter-qt yourself, there are some useful files here.

## etter: URI support ##


etter-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install etter-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your etterqt binary to `/usr/bin`
and the `../../share/pixmaps/etter128.png` to `/usr/share/pixmaps`

etter-qt.protocol (KDE)

