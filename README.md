# AoC Times of the New Rome - More Fonts
Lets you use custom fonts for the game, as well as letting you change outline settings.

# Features
```
{
    "NormalText": "Vanilla",
    "Title" : "Vanilla",
    "BoldText" : "Vanilla",
    "MapText" : "Vanilla",
    "LargeMapText" : "Vanilla",
    "NormalTextUnderlay" : "Vanilla",
    "ForceVanillaValues" : false,
    "MapTextOutlineWidth" : 0.25,
    "MapTextOutlineSoftness" : 0.1,
    "MapTextOutlineColor": {
        "r": 0,
        "g": 0,
        "b": 0,
        "a": 255
        },
    "MapTextColor": {
        "r": 255,
        "g": 255,
        "b": 255,
        "a": 255
    },
    "LargeMapTextOutlineWidth" : 0.25,
    "LargeMapTextOutlineSoftness" : 0.1,
    "LargeMapTextOutlineColor": {
        "r": 255,
        "g": 255,
        "b": 255,
        "a": 255
        },
    "LargeMapTextColor": {
        "r": 0,
        "g": 0,
        "b": 0,
        "a": 255
    }
}
```
Edit Font Settings.json however you'd like to change game appearance. If the name of the font in the json doesn't match the name of the FOLDER of the font, then the mod will resort to the vanilla font and ignore you until you learn to spell properly, tsk tsk.

MapText = Cities and Small Nations
LargeMapText = Big Nations

To add your own fonts just go to the mod's Fonts folder and create a new folder with a .otf or .ttf file inside. You can find these easily by just searching "[FONT YOU WANT TO DOWNLOAD] download". The folder itself can be named anything you'd like and does not have to match the file inside. If you include multiple files in the folder, the mod will just go with the first one it sees.

# Planned Features
- Real-time editing instead of having to close the game to edit the json and have the changes apply.
- Even more customization options
- Automatic scenario-specific font setting linkage

## Requirements
- BepInEx 5 x64 (Mono). Download from the official BepInEx releases. https://github.com/bepinex/bepinex/releases

## Install
1. Extract the BepInEx zip into the game folder (next to the exe). Run the game once.
2. Extract **this mod’s zip** into the plugins location so that:
   - BepInEx\plugins\Times of the New Rome - More Fonts exists
3. Run the game. Check `BepInEx/LogOutput.log` for "Times of the New Rome - More Fonts loaded".
