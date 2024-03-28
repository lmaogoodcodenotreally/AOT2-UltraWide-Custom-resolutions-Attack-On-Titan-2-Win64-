## Welcome!

- _Q:_ Why does this repo exist?
- _A:_ Because game developpers are too lazy to make their game adapt to all resolution for PC players.

- _Q:_ Does this repo contain any Koei Tecmo Games intellectual propreties ?
- _A:_ Hell nah, we don't redistribute Koei Tecmo Games files or intelletual propreties, we simply wanna help people with legit copies getting their game running well!


# Patching steps:

- Download any Hex Editor. (Any will work, I use HxD & HexWorkshop)
- Copy your AOT region executable to a new folder (name of exe is either: `AOT2_AS.exe`, `AOT2_EU.exe`, `AOT2_JP.exe`)
- Now open that exe into Hex editor and search for `000F7008` (`000F7008` == `3840x2160`)
- Check table below & insert your choosen resolution instead of `000F7008` (Exemple: `700DA005` == `3440x1440`)
- Make sure to create a backup of your game, now that you edited the value, make sure to save, then start the game as normal.
- In Main Menu, go to `System >> Graphics >> Resolutions`, then set it to your custom one, then set display mode to `Windowed`
- Now all you have to do, is create a txt file, and inside put your resolution value (exemple: `700DA005`) so you know what to edit if you need to switch back to normal
- HAVE FUN !



# Resolutions


| Hex Value | Resolution  |
|-----------|-------------|
| 8007B004  | 1920x1200   |
| 000A4006  | 2560x1600   |
| 000A3804  | 2560x1080   |
| 000C0003  | 3072x768    |
| 700DA005  | 3440x1440   |
| 000F0004  | 3840x1024   |


Feel free to make pulls with more resolution hex value!

