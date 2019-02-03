[Installation and Download](index#installation) · [Levels](levels.md) · [Level Editing](index#editing-levels) · [Github](https://github.com/pfgithub/goilevelmod)

# [Level Maker Mod](https://pfgithub.github.io/goilevelmod) by [FM2 and others](credits.md)
For Getting Over It with Bennett Foddy 

## Installation

Download the latest version from the [Releases page](https://github.com/pfgithub/goilevelmod/releases). Get the normal DLL for a standard install, or the GOIMP DLL if you have the [multiplayer mod](https://forum.facepunch.com/f/games/ujqm/Try-my-multiplayer-mod-for-Getting-Over-It-with-Bennett-Foddy/5/) installed.

#### Windows/Linux

Right click Getting Over It on Steam and go to Properties > Local Files > Browse Local Files > GettingOverIt_Data > Managed.  
Delete `Assembly-CSharp.dll`. Move the modded DLL there and rename it `Assembly-CSharp.dll`.

#### Mac (untested)

Right click Getting Over It on Steam and go to Properties > Local Files > Browse Local Files > GettingOverIt.app > Right Click > View Package Contents > Find a folder called Managed somewhere, maybe under resources or something. 
Delete `Assembly-CSharp.dll`. Move the modded DLL there and rename it to `Assembly-CSharp.dll`.

#### iOS/Android

Not Supported

## Loading Levels

Find a level you want on the [levels page](levels.md). Click Get Code and copy the level code to your clipboard.  
Run Getting Over It and select New Game. Press `CTRL`+`V` to load the level from your clipboard into the game.

## Editing Levels

Run Getting Over It and select New Game to make a level. If a level is already loaded, copy `blank` and paste it in-game to clear the level.

### Editing Mode

`E` - Toggle editing mode.  
`Left Click` - Place a block at your cursor.  
`Right Click` - Delete a block under your cursor.  
`Scroll Wheel` - Switch blocks.  
`Middle Click` - Set end point.  
`WASD` - Move
Hold `Left Click` and press `Right Click` - Move starting point.

Stack blocks in a certain direction by clicking in the direction you want to stack on another block. [Screenshot](https://i.imgur.com/fXKT5Ld.png)

**Blocks**:
- White - Default
- Aqua - Ice (0 friction)
- Red - Background (no collision)
- Light Purple - Circle
- Pure White - Text (Edit text with the "Demo Text" field in the top left corner)
- Gray - Falling Block

**Toggles**  
Flying - Enables/disables flying with WASD while in playing mode.  
Zooming - Enables/disables zooming with `Up`/`Down` while in playing mode.  

> Note: You cannot save your level with Flying or Zooming enabled.

Editing - Enables/disables editing your level.

> Note: After you disable editing, you cannot go back into editing mode again. Keep it enabled.

Mode - Choose gravity (Original/Space/Right)

### Playing Mode

`WASD` - Fly (when enabled in editing mode)
`Up`/`Down` - Zoom In/Out (when enabled in editing mode)

### Saving and Loading Levels  

> **Important Note**: You cannot save your level until you beat them. Your level will automatically be copied once you beat it. See [verifying levels](#verifying-levels) for more information.

`Ctrl+C` = Copy level code to clipboard  
`Ctrl+V` = Load level from clipboard

### Verifying Levels

Before you can save your level, you have to verify it. Make sure both flight and zoom are disabled. Exit editing mode and press `CTRL`+`R` to start verifying. Once you beat your level, it will be copied so you can share it.

### Sharing levels  

#### [Issue](https://github.com/pfgithub/goilevelmod/issues)

Create an issue containing your level name, the author name, the level code, the difficulty, and the length.

#### [Pull Request](https://github.com/pfgithub/goilevelmod)

Add a new file `levels/levelname.txt` containing your level code. Edit [levels.md](https://github.com/pfgithub/goilevelmod/blob/master/levels.md) to add a row containing your level info.

#### Discord

@me and I'll add it. I'm on the GOI reward discord, speedrun discord, and GOIMP discord as pfg#4865.


## Screenshots

[![simple level](https://i.imgur.com/sSwaKIh.jpg)](https://i.imgur.com/sSwaKIh.jpg)
[![simple level](https://i.imgur.com/pl3kn0s.png)](https://i.imgur.com/pl3kn0s.png)
