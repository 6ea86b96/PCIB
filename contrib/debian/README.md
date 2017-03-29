
Debian
====================
This directory contains files used to package pcibd/pcib-qt
for Debian-based Linux systems. If you compile pcibd/pcib-qt yourself, there are some useful files here.

## pcib: URI support ##


pcib-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pcib-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pcibqt binary to `/usr/bin`
and the `../../share/pixmaps/pcib128.png` to `/usr/share/pixmaps`

pcib-qt.protocol (KDE)

