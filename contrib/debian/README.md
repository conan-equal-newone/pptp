
Debian
====================
This directory contains files used to package pptpd/pptp-qt
for Debian-based Linux systems. If you compile pptpd/pptp-qt yourself, there are some useful files here.

## pptp: URI support ##


pptp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pptp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pptp-qt binary to `/usr/bin`
and the `../../share/pixmaps/pptp128.png` to `/usr/share/pixmaps`

pptp-qt.protocol (KDE)

