# AUCOP

AUCOP is...
An Unfortunate Collection Of Plugins

It's a collection of OpenSource audio plugins, which are (at inception) based on Pure Data and the Camomile plugin API (which itself uses libpd). Most plugins are based on "Vanilla" Pd, which is a prerequisite of Camomile.

### Installation
All plugin subfolders are organized as follows:

- /PD/ ... the orginal Pure Data patch and support files. Copy this folder anywhere, then load the <plugin_name>.pd file in Pure Data.
- /Camomile/ ... the Camomile plugin source files. Place /<plugin_name>/ in the Camomile/Examples folder, and invoke Camomile as required for the target OS.
- /plugins_linux/ ... binary plugins built for EXT4 64 bit systems (Debian Buster). If you don't want to generate the plugins, simply copy /<plugin_name>.lv2/ to ./.lv2/, or the LV2 system folder. Likewise, copy the plugin within the /vst/ folder to ./.vst/ to install the vst2 version.

### About Camomile and AUCOC

Camomile affords encapulation of Pure Data patches within the plugin formats for multiple platforms (Linux, Mac, Windows). Currently only the Linux binary plugins are included (this will likely change), but using the source folders to generate the plugins is encourages. See the instructions above in *Installation*.

Learn to create new Camomile plugins [here](https://github.com/pierreguillot/Camomile/wiki/How-to-create-new-plugins).

All Camomile plugins with guis have an extra documentation tab that's accessed by clicking on the camomile flower in the upper left corner of the GUI:
![flower](https://user-images.githubusercontent.com/1409918/37906678-2b998b0a-3103-11e8-946a-10df0f3d2eca.png)

Links:

- [Camomile](https://github.com/pierreguillot/Camomile)
- [libpd](https://github.com/libpd)
- [Pure Data](https://puredata.info/)

Thanks! Later,   
Doug Garmon
