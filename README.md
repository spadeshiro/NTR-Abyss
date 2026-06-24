# NTR-Abyss English Fanpatch
<img width="1400" height="622" alt="NTRAbyss-large" src="https://github.com/user-attachments/assets/1c1406dc-715b-493a-b1da-d7c91425e2e7" />
English Fanpatch for a certain PC version of a pixel game made by Mr. Black Bear, powered by XUnity.AutoTranslator on top of BepinEx.  

## Contributors
- SpadesHiro
- Abaddon
- Scopolamin
- Shimpfiedrice
- Cornelia

## Features
- Translated most of the UI
- Translations for gameplay-related stuff, eg. character kits, abyss mode, brothel minigame, etc.
- Story translation

## Installation
1. **(For old users)** Delete BepinEx folder inside your `dotabyss_x_cl` folder
2. Download the [latest release build](https://github.com/spadeshiro/NTR-Abyss/releases)
3. Extract to your Dot Abyss installation folder, replace files if asked

## Uninstallation
In case you're no longer interested in the English patch or you're having issues trying to run it (as it's pretty heavy for low-end PC), uninstalling the patch is as easy as removing these files:
- BepinEx folder
- Dotnet folder
- winhttp.dll
- .doorstop_version
- doorstop_config.ini

The patch itself doesn't alter or break any of the in-game files, there's no extra steps required to make sure the game is fully back to vanilla state.

## Current Limitation
- In case you're asking, no, we don't plan on making android version as we lack the expertise and manpower.
- BepinEx + XUnity.AutoTranslator is known to be taxing in term of performance. There's nothing we can do about it.
- Texture translation is currently not feasible due to how hard it is to dump them properly.

## Troubleshooting
- If you're experiencing C++ Runtime Error, consider trying to [enable "Unicode UTF-8 for Worldwide Language Support"](https://www.elevenforum.com/t/enable-or-disable-unicode-utf-8-for-worldwide-language-support-in-windows-11.38649/), this has solved many users.
- If the console log seems to be stuck, make sure you didn't accidentally click on it as doing so will halt the process including the game itself.
- Windows Defender may consider BepinEx a threat, you can fix this by temporarily disabling Defender or whitelisting Dot Abyss folder.

This translation is powered by [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) on top of [BepinEx](https://github.com/BepInEx/BepInEx). Without these two, this translation would never happen.
