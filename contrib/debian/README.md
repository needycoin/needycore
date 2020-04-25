
Debian
====================
This directory contains files used to package needycoind/needycoin-qt
for Debian-based Linux systems. If you compile needycoind/needycoin-qt yourself, there are some useful files here.

## needycoin: URI support ##


needycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install needycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your needycoinqt binary to `/usr/bin`
and the `../../share/pixmaps/needycoin128.png` to `/usr/share/pixmaps`

needycoin-qt.protocol (KDE)

