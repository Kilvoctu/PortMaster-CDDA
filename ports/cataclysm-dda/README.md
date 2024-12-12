## Notes

Thanks to the [Cataclysm DDA Team](https://github.com/CleverRaven/Cataclysm-DDA) for creating such an awesome game and making it available for free.
This is based on the 0.H-RELEASE Herbert build, available [here.](https://cataclysmdda.org/releases/)

## Controls

| Button | Action |
|--|--| 
|Select+L1|See the button bindings at any point in-game|
|Dpad|Movement|
|L1/L2+Dpad|Diagonal Movement|
|A|Confirm / Action Menu|
|B|Cancel / Main Menu|
|X|Examine|
|Y|Inventory|
|R1|Aim Weapon|
|R2|Use Wielded Item|
|R3|Smash|
|L3|Look|
|Left Stick Up|Ascend Stairs|
|Left Stick Down|Descend Stairs|
|Left Stick Left|Close Door|
|Left Stick Right|Peek|
|Right Stick Up|Zoom In|
|Right Stick Down|Zoom Out|
|Right Stick Left|Menu Tab Left / Change Movement Mode|
|Right Stick Right|Menu Tab Right / Attack|
|Select|Pass Turn|
|Start|Map|
|--|--|
|Select+A|Butcher|
|Select+B|Ignore Enemy|
|Select+X|List Nearby Items|
|Select+Y|Unload Item|
|--|--|
|L1+X|Pick Up Nearby Items|
|L1+Y|Drop Item|
|L1+R1|Reload Weapon|
|L1+R2|Wield Item|
|L1+R3|Grab|
|L1+L3|Compare Two Items|
|L1+Left Stick Up|Mutations|
|L1+Left Stick Down|Bionics|
|L1+Left Stick Left|Toggle Safe Mode|
|L1+Left Stick Right|Sort Armor|
|L1+Right Stick Up|Use Item|
|L1+Right Stick Down|Consume Item|
|L1+Right Stick Left|Take Off Item|
|L1+Right Stick Right|Wear Item|
|L1+Select|Wait|
|L1+Start|Player Info|
|--|--|
|L2+X|Insert Item|
|L2+Y|Unload Container|
|L2+R1|Throw Weapon|
|L2+R2|Toggle Item Attack Mode|
|L2+R3|Haul|
|L2+L3|Open Diary|
|L2+Left Stick Left|Zone Manager|
|L2+Left Stick Right|Zone Activities|
|L2+Right Stick Up|Advanced Inventory|
|L2+Right Stick Down|Construction|
|L2+Right Stick Left|Disassemble Item|
|L2+Right Stick Right|Craft Item|
|L2+Select|Sleep|
|L2+Start|Message Log|
|--|--|
|Start+Down|Text Input|
|Up|Previous letter (while in Text Input)|
|Down|Next letter (while in Text Input)|
|Left|To next character (while in Text Input)|
|Right|Delete and move to previous character" (while in Text Input)|
|Select|Cancel and exit (while in Text Input)|
|A / Start|Enter and exit (while in Text Input)|


## Compile

```shell
git clone --depth 1 --branch 0.H-PM https://github.com/Kilvoctu/Cataclysm-DDA.git
cd Cataclysm-DDA
make TILES=1 SOUND=1 RELEASE=1 LOCALIZE=1 LANGUAGES=all
```
