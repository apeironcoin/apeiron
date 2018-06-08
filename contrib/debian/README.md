
Debian
====================
This directory contains files used to package apeirond/apeiron-qt
for Debian-based Linux systems. If you compile apeirond/apeiron-qt yourself, there are some useful files here.

## apeiron: URI support ##


apeiron-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install apeiron-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your apeironqt binary to `/usr/bin`
and the `../../share/pixmaps/apeiron128.png` to `/usr/share/pixmaps`

apeiron-qt.protocol (KDE)

