==Instructions==

Install Ago's mod loader. You can find it here: http://forum.wurmonline.com/index.php?/topic/133085-alpha-single-player-priest-mod-mod-

loader/

Unzip this archive into the mod/ folder.

You should see a set up like this when done:

(Replace dedicated server with Wurm Unlimited\WurmServerLauncher\ for bundled servers)
Wurm Unlimited Dedicated Server\mods\deedmod.properties
Wurm Unlimited Dedicated Server\mods\deedmod\
Wurm Unlimited Dedicated Server\mods\deedmod\DeedMod.jar

Start your server with the batch file provided with Ago's loader: modlauncher.bat

Profit!

See deedmod.properties for settings.

__Changelog__

Feb 11th 2019:
- Forked project to github
- Fixed an instance of the mod ignoring the powerOverride config when counting deeds owned by a steam ID.

Jan 29th, 2019: (Before github fork)
- Update to work with Wurm Unlimited 1.8.0.3
- Added functionality to ignore deeds from GM characters with power equal to or greater than powerOverride in total deed count.
