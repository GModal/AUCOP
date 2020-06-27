# AUCOP

AUCOP is...
An Unfortunate Collection Of Plugins

It's a collection of OpenSource audio plugins, which are (at inception) based on Pure Data and the Camomile plugin API (which itself uses libpd). All the plugins are based on "Vanilla" Pd, which is a prerequisite of Camomile.

All plugin subfolders are organized as follows:

- /PD/ ... the orginal Pure Data patch and support files.
- /Camomile/ ... the Camomile plugin files. Place /AUCOP-guitarToy16x/ in the Camomile/Examples folder, and invoke Camomile as required for the target OS.
- /plugins_linux/ ... binary plugins built for EXT4 64 bit systems (Debian Buster). Copy /AUCOP-guitarToy16x.lv2 to ./.lv2, or the LV2 system folder.


Links:

- [Camomile](https://github.com/pierreguillot/Camomile)
- [libpd](https://github.com/libpd)
- [Pure Data](https://puredata.info/)
