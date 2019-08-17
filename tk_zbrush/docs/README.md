## tk_zbrush
###### *Customized ZBrush UI and toolkit.


![alt text](https://raw.githubusercontent.com/m3trik/tk_zbrush/master/tk_zbrush/docs/UI_ZBrush.png)



## Design:
######
**

*continual work in progress..*





##
-----------------------------------------------
 Installation:
-----------------------------------------------
######
(Assuming the directory structure is left default).


* add files to zbrush's plugin directory at %programfiles%\Pixologic\ZBrush 20xx\ZStartup\ZPlugs64


Then after launching ZBrush:
set up the ui:
* navigate to preferences> config> load ui, and load the ui config file 'tk_ui_x.xx.cfg' found at %programfiles%\Pixologic\ZBrush 20xx\ZStartup\ZPlugs64\tk_zbrush.
* preferences> config> store config

(after initially running the 'defaultZScript' startup script, and storing the settings, you can comment out those preferences that you don't usually need to run at startup.)

hotkeys:
* preferences> hotkeys> load, file 'tk_hotkeys_x.x.txt' found in the same folder previously used.
* preferences> hotkeys> store

color prefs:
* preferences> icolors> load, file 'tk_ui_color_x.x.cfg' found in the same folder previously used.