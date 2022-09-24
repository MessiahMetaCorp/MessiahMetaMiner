
Debian
====================
This directory contains files used to package messiahmetacorpd/messiahmetacorp-qt
for Debian-based Linux systems. If you compile messiahmetacorpd/messiahmetacorp-qt yourself, there are some useful files here.

## messiahmetacorp: URI support ##


messiahmetacorp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install messiahmetacorp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your messiahmetacorp-qt binary to `/usr/bin`
and the `../../share/pixmaps/messiahmetacorp128.png` to `/usr/share/pixmaps`

messiahmetacorp-qt.protocol (KDE)

