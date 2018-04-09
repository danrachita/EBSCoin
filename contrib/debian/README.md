
Debian
====================
This directory contains files used to package ebsd/ebs-qt
for Debian-based Linux systems. If you compile ebsd/ebs-qt yourself, there are some useful files here.

## ebs: URI support ##


ebs-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ebs-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ebsqt binary to `/usr/bin`
and the `../../share/pixmaps/ebs128.png` to `/usr/share/pixmaps`

ebs-qt.protocol (KDE)

