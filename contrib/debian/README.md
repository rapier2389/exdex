
Debian
====================
This directory contains files used to package exdexd/exdex-qt
for Debian-based Linux systems. If you compile exdexd/exdex-qt yourself, there are some useful files here.

## exdex: URI support ##


exdex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install exdex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your exdexqt binary to `/usr/bin`
and the `../../share/pixmaps/exdex128.png` to `/usr/share/pixmaps`

exdex-qt.protocol (KDE)

