# AUCOP

AUCOP is...
#### *An Unfortunate Collection Of Plugins*

It's a collection of open source audio plugins, which are (at inception) based on Pure Data and the Camomile plugin API (which itself uses libpd). Most plugins are based on "Vanilla" Pd, which is a prerequisite of Camomile. 

Some plugins also utilize MobMuPlat, which is an opensource API for creating interfaces on mobile devices. MobMuPlat has great networking hooks, and is OSC capable.

### Installation
All plugin subfolders are organized as follows:

- /PD/ ... the orginal Pure Data patch and support files. Copy this folder anywhere, then load the <plugin_name>.pd file in Pure Data.
- /Camomile/ ... the Camomile plugin source files. Place /<plugin_name>/ in the Camomile/Examples folder (or Camomile/Plugins/Examples/), and invoke Camomile as required for the target OS. Follow the instructions on the Camomile site for each OS to install from the /builds/ folder (it's different for each OS).
- /plugins_linux/ ... binary plugins built for EXT4 64 bit systems (Debian Buster). If you don't want to generate the plugins, simply copy /<plugin_name>.lv2/ to <user home>/.lv2/, or the LV2 system folder. Likewise, copy the plugin within the /vst/ folder to <user home>/.vst/ to install the vst2 version.
  
I prefer the user acct local installs, as that allows for easy editing of the preset files that accompany some plugins.

### About Camomile and AUCOC

Camomile affords encapulation of Pure Data patches within different plugin formats for multiple platforms (Linux, Mac, Windows). Currently only the Linux binary plugins are included (this will likely change), but using the source files to generate the plugins for other platforms is encouraged. See the instructions above in *Installation*.

Learn how to create new Camomile plugins [here](https://github.com/pierreguillot/Camomile/wiki/How-to-create-new-plugins).

All Camomile plugins with guis have an extra documentation tab that's accessed by clicking on the chamomile flower in the upper left corner of the GUI. 
<img src="https://user-images.githubusercontent.com/1409918/37906678-2b998b0a-3103-11e8-946a-10df0f3d2eca.png" width="25"> One tab displays the contents of the plugin-defined "description" file -- "Info.txt" in the plugin folder is the conventional name.

---

### Links:

- [Camomile](https://github.com/pierreguillot/Camomile)
- [MobMuPlat](http://www.danieliglesia.com/mobmuplat/)
- [libpd](https://github.com/libpd)
- [Pure Data](https://puredata.info/)

Thanks! Later,   
*Doug Garmon*
