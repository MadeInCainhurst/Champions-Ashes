******************
* ASHES LAUNCHER *
******************

Installing, updating, enabling, and disabling is all handled by the launcher now.
Place the launcher in your root game directory and launch it.

TIP:
\AshesLauncher\Disabled
Any files in this folder will be copied to your game directory when you disable the mod.
For example if you put WexDust's dinput8.dll there it will enable it when you disable the mod.

Files starting with _ will be ignored and won't be copied over to the main game directory.

LEGACY_INSTALLATION
------------
Unzip the downloaded file, then place:
		
	_ashes (the whole folder) 
	dinput8.dll
	modengine.ini
	HoodiePatcher.dll
	HoodiePatcher.ini

in your root game directory. (where the darksoulsIII.exe is)

After, go in your modengine.ini, search for the following:

"chainDInput8DLLPath="\"

and replace it with this:

"chainDInput8DLLPath="\HoodiePatcher.dll".
LEGACY_UNINSTALLATION
--------------
Rename the "dinput8.dll" file to something else, like "disable_dinput8.dll", and remove the HoodiePatcher.dll from the game folder.
This will completely disable the mod and return your game to its vanilla state.


IMPORTANT NOTE
--------------
This mod WILL ban you if you have it enabled and launch the game. 
Make sure it's disabled before using a character that you don't want banned.

LINKS
-----
Changelog:	https://bit.ly/ashes-changelog 
Nexus Page:	https://www.nexusmods.com/darksouls3/mods/488
Discord:	https://discord.gg/TQy6ubN
Twitter:	https://twitter.com/championsashes