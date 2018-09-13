
Debian
====================
This directory contains files used to package mrqd/mrq-qt
for Debian-based Linux systems. If you compile mrqd/mrq-qt yourself, there are some useful files here.

## mrq: URI support ##


mrq-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mrq-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mrqqt binary to `/usr/bin`
and the `../../share/pixmaps/mrq128.png` to `/usr/share/pixmaps`

mrq-qt.protocol (KDE)

