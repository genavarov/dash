
Debian
====================
This directory contains files used to package bashd/bash-qt
for Debian-based Linux systems. If you compile bashd/bash-qt yourself, there are some useful files here.

## bash: URI support ##


bash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bash-qt binary to `/usr/bin`
and the `../../share/pixmaps/bash128.png` to `/usr/share/pixmaps`

bash-qt.protocol (KDE)

