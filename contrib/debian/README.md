
Debian
====================
This directory contains files used to package allcoingurud/allcoinguru-qt
for Debian-based Linux systems. If you compile allcoingurud/allcoinguru-qt yourself, there are some useful files here.

## allcoinguru: URI support ##


allcoinguru-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install allcoinguru-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your allcoinguru-qt binary to `/usr/bin`
and the `../../share/pixmaps/allcoinguru128.png` to `/usr/share/pixmaps`

allcoinguru-qt.protocol (KDE)

