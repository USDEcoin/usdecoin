
Debian
====================
This directory contains files used to package usdecoind/usdecoin-qt
for Debian-based Linux systems. If you compile usdecoind/usdecoin-qt yourself, there are some useful files here.

## usdecoin: URI support ##


usdecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install usdecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your usdecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/usdecoin128.png` to `/usr/share/pixmaps`

usdecoin-qt.protocol (KDE)

