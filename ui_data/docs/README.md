## tk_zbrush
###### *A custom ZBrush UI.


![alt text](https://raw.githubusercontent.com/m3trik/zbrush-ui/master/ui_data/docs/UI_ZBrush.png)



## Design:
######
**

*work in progress..*





##
-----------------------------------------------
 Installation:
-----------------------------------------------
######
(Assuming the directory structure is left default, and substituting the correct ZBrush version).
* add files to zbrush's plugin directory at %programfiles%\Pixologic\ZBrush 20xx\ZStartup\ZPlugs64

Then after launching ZBrush: <br />
Load and store the ui:
* On the main menu bar: navigate to Preferences> Config> Load Ui, to load the file 'ui_config_x.xx.cfg' found in the 'ui_data' folder.
* Preferences> Config> Store Config.

Set the startup state: <br />
* ZScript> Load> load 'startup.txt' in the 'ui_data' folder.

Load the color config: <br />
* preferences> icolors> load, file 'ui_color_x.x.cfg' also found in the 'ui_data' folder.
