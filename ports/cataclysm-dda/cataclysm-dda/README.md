## Notes

Thanks to the [Cataclysm DDA Team](https://github.com/CleverRaven/Cataclysm-DDA) for creating such an awesome game and making it available for free.
This is based on the 0.H-RELEASE Herbert build, available [here.](https://cataclysmdda.org/releases/)

## Controls

| Button | Action |
|--|--| 
|Hotkey|Open in-game controls help screen for full button mappings|
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
|Start+Down|Text Input|
|Up|Previous letter (while in Text Input)|
|Down|Next letter (while in Text Input)|
|Left|To next character (while in Text Input)|
|Right|Delete and move to previous character" (while in Text Input)|
|Select|Cancel and exit (while in Text Input)|
|A / Start|Enter and exit (while in Text Input)|
|--|--|
|While Aiming|--|
|X|Switch Fire Mode|
|Y|Switch Ammo|
|R1|Fire|
|R2|Aimed Shot|
|L1+R2|Careful Shot|
|L2+R2|Precise Shot|
|R3|Snap to Target|
|Right Stick Left|Previous Target|
|Right Stick Right|Next Target|
|Select|Increase Aim|
|Start|Reset Aim|


## Compile

```shell
git clone --depth 1 --branch 0.H-branch https://github.com/CleverRaven/Cataclysm-DDA.git
cd Cataclysm-DDA
make TILES=1 SOUND=1 RELEASE=1 LOCALIZE=1 LANGUAGES=all
```
