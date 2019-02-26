
Debian
====================
This directory contains files used to package ggpd/ggp-qt
for Debian-based Linux systems. If you compile ggpd/ggp-qt yourself, there are some useful files here.

## ggp: URI support ##


ggp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ggp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ggpqt binary to `/usr/bin`
and the `../../share/pixmaps/ggp128.png` to `/usr/share/pixmaps`

ggp-qt.protocol (KDE)

