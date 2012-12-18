# Plugin to Open in Sublime Text 2 for Pathfinder #

Based on - [Plugin for Textmate by Orta](https://github.com/orta/pathfinder_open_in_textmate)

Installation, Download the compiled file from [this link](https://github.com/ramkola/pathfinder_open_in_sublime/blob/master/pathfinder_open_in_sublimetext.plugin.zip?raw=true).  Unzip and copy the plugin file into ~/Library/Application Support/Path Finder/PlugIns folder

Restart Path Finder.  You will find "Open with Sublime" item under the Commands menu >  Plugins section.  In Path Finder, select any file or folder and use the above menu item.  The selected file will open in Sublime Text.

To compile the code, clone the repository, download the [Path Finder SDK](http://get.cocoatech.com/PathFinderSDK.zip) and compile the code using XCode.  After you build the code, you can right-click on the product in XCode to open the folder location in finder and then copy the .plugin file into ~/Library/Application Support/Path Finder/PlugIns folder.