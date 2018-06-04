
Debian
====================
This directory contains files used to package goldkashd/goldkash-qt
for Debian-based Linux systems. If you compile goldkashd/goldkash-qt yourself, there are some useful files here.

## goldkash: URI support ##


goldkash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install goldkash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your goldkash-qt binary to `/usr/bin`
and the `../../share/pixmaps/goldkash128.png` to `/usr/share/pixmaps`

goldkash-qt.protocol (KDE)

