## Giga Inventory Mod

This mod expands the stash, cube, and inventory of a character

### Installation

1. Backup your characters and the game folder before making any changes.

2. Download the most recent release from the [releases page](https://github.com/cyhyraethz/d2-giga-inv/releases) and extract the files.

3. Copy the extracted data folder for the version you would like to use into the game folder, which should be located in `C:\Program Files (x86)\Diablo II`, and select merge if prompted.

4. Add the parameters `-direct` and `-txt` to the shortcut you use for launching the game. You can do that by right clicking on the shortcut, selecting `Properties`, typing ` -direct -txt` after the file path in the `Target:` text box, and clicking `OK`. Make sure to leave a space after the file path and between `-direct` and `-txt`.

   If you use PlugY you can also achieve this by adding `-direct -txt` after `Param=` in the PlugY config file, PlugY.ini, so that it looks like this: `Param=-direct -txt`.

   If you use Lutris to play the game on Linux you can do this by right clicking on the game in Lutris, selecting `Configure`, clicking on the `Game options` tab, adding `-direct -txt` to the `Arguments` text box, and clicking `Save` in the bottom right corner.

5. If you are adding this mod to an existing data folder, delete the .bin files in `Diablo II\data\global\excel` before launching the game so that new ones can be generated from the text files.

### Warning

Items may be lost if character is used in a game with standard inventory size

### Credits

Mhoram (For Diablo2-LOD v1.09)

Ravenswolf (Updated for Diablo2-LOD v1.10)

Based on Extended Stash Mod (from [The Phrozen Keep](https://d2mods.info/home.php))
