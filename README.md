# AMXX-Browser
An AMXX Plugin Manager for Windows

The idea of AMXX Browser is to keep alive the work of the "AMX Mod X" community for a long time (even if websites and forums disappear in the futur).

It also offers some functionalities to use AMXX plugins in an easy way.

AMXX Browser has the following objectives : 
- An offline brower for AMXX plugins with visual illustrations
- Select quickly the AMXX plugins you want to activate and make presets.
- An installer for AMXX
- May be in the futur a server launcher (which allow to launch with a selected template of activated plugins).

AMXX Browser is designed to be open source, easily editable and participative :
Hta application can be modified without any IDE/compilator, it is only a text file with html, js and vbscript.

Everyone can easily publish new plugin which will be added to the repository. To do this just duplicate the plugin template and edit it.
Please use the issues section of this github repository to submit new packages. 

![Image description](https://i.imgur.com/i9sHGA7.png)

AMXX-Browser is also a nice exemple to use hta in a modern way : it include some powerful libraries as jquery, [bootstrap 3](https://www.bootstrapcdn.com/legacy/bootswatch/), [datatables](https://datatables.net/) , [video-js](https://github.com/videojs/video.js) and [gifffer](https://github.com/krasimir/gifffer).

Thanks to [monolith](https://github.com/Y2Z/monolith) AMXX-Browser is also able to backup an html page in a single file.

How to use :
- Run "Launcher.hta" (Windows only, 7/8/10 should be OK)
- Select the plugin you want to include in a preset with checkboxs at the right of table
- Then click on "save as new" and put a name
- You've done a new preset ! 
- To try your preset, rename it plugins.ini and put it here addons\amxmodx\configs\ 

How to add an AMXX :
- create a new directory in AMXX-Browser\plugins and name it with the plugin name
- create a description.ini with all the informations (open "Bad Camper 1.4.239" example for more informations)
- create a preview of the plugin (it can be preview.jpg, preview.png , .gif or .mp4). GifCam is in Tools directory to makes GIF easily.
- put .sma and if you have .amxx files in AMXX-Browser\Plugins\My_new_plugin\files
- press F5 in hte application to refresh it, you should see your new plugin in the interface.


