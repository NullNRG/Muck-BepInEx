# Muck-BepInEx

Installation:
clone or download this repository ( or if you dont know how, click here: https://github.com/NullNRG/Muck-BepInEx/archive/refs/heads/main.zip ), 

copy all the files from the "Muck-BepInEx-main" folder in the archive, into the root of the Muck game directory.
if it asks to replace any files, yeah, do that. if it's a fresh install, shouldnt need to.

ex: "your steam installation path"\steamapps\common\Muck

run Muck.

Plugins are located in BepInEx\plugins
Plugin config files (if plugin supports it ) in BepInEx\config

By default, i have included a plugin that gives you god mode. if you dont want it, delete the MuckGod plugin.



--------- Visual Studio Template / MuckTemplate

In the file "GameDir.targets", be sure to changle the line to match your installation path. " <GameDir>yoursteampath\steamapps\common\Muck</GameDir> "
and be sure to have your publicised assemblies in tact.
By default, i have included some plugins from their respective authors,
to create these publicised assemblies for you, when you first launch the game with BepInEx installed.
This template is not needed if you only intend to play with the mods, and not develop them. so you can safely delete the MuckTemplate folder.








Last but not least,



Muck..
