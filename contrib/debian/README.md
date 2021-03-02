
Debian
====================
This directory contains files used to package cryptcored/cryptcore-qt
for Debian-based Linux systems. If you compile cryptcored/cryptcore-qt yourself, there are some useful files here.

## cryptcore: URI support ##


cryptcore-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptcore-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptcore-qt binary to `/usr/bin`
and the `../../share/pixmaps/cryptcore128.png` to `/usr/share/pixmaps`

cryptcore-qt.protocol (KDE)

