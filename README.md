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

Run Getting Over It and select New Game to start editing a level.

### Gravity  
Use `WASD` to fly, flying will reset the gravity.  
`O` = Standard Gravity  
`I` = Right Gravity  
`P` = Space% Gravity  

### Placing Blocks  
Pause the game to place blocks. Blocks will be placed at your mouse cursor.  
`E` = Place white block. Normal friction.  
`Alt`+`E` = Place red block. No collision.  
`Shift`+`E` = Place aqua ice block. Zero friction.  
`Ctrl`+`E` = Place purple circle. Normal friction.  
`R` = Move the ending block. Ends the game when touched with the pot.  

### Saving and Loading Levels  
`Ctrl+C` = Copy level code to clipboard  
`Ctrl+V` = Load level code  

### Sharing levels
See [CONTRIBUTING.md](https://github.com/pfgithub/goilevelmod/blob/master/CONTRIBUTING.md)
