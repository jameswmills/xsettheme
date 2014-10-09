xsettheme
=========

Small python/gtk3 app to dynamically set the GTK theme for xsettingsd

10/09/2014 - Initial commit.  Plenty more to do (and tighten up), but it is a start!

* Basic theme parsing/changing functionality
* No preferences dialog
* xsettings config hardcoded to ~/.xsettingsd
* Finds all gtk 3.0 compatible themes from ~/.themes and /usr/share/themes
* reinitializes xsettingsd with a simple 'killall -HUP'
