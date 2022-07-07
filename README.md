# tmyt
**Terminal youtube client**

Small script to select videos in terminal and watch them with mpv.

<img src="screenshot.png" alt="drawing" width="700" align="center" />

**Features**
+ Choose video quality
+ Download/watch videos
+ Audio playback/download

**Dependencies**
+ mpv (for watchling online)
+ yt-dlp (for downloading)

**Installation**
+ `wget https://raw.githubusercontent.com/tzrn/tmyt/main/tmyt`
+ `chmod +x tmyt`
+ `sudo mv tmyt /bin/tmyt`


**Usage**
+ `tmyt kittens` searches for kittens; plays selected
+ `tmyt -da kittens` searches for kittens; downloads audio of selected
+ To get whiptail colorscheme as shown on screenshot add following to your shell startup script (.bashrc .zshrc etc.)

```
export NEWT_COLORS='root=,black
border=red,black 
title=red,black
roottext=red,black
window=red,black 
textbox=white,black
compactbutton=white,black
listbox=white,black
actlistbox=black,white
actsellistbox=black,red'
```
