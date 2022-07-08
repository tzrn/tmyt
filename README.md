# tmyt
**Terminal youtube client**

Small script to select videos in terminal and watch them with mpv.

<img src="screenshot.png" alt="drawing" width="700" align="center" />

**Features**
+ Terminal user interface
+ Download/watch videos
+ Video quality selection
+ Audio playback/download
+ History, Favorite channels

**Dependencies**
+ mpv (for watchling online)
+ yt-dlp (for downloading)

**Installation**
+ `$wget https://raw.githubusercontent.com/tzrn/tmyt/main/tmyt`
+ `$chmod +x tmyt`
+ `#mv tmyt /bin/tmyt`

**Usage**
+ `tmyt` opens defaut menu
+ `tmyt kittens` searches for kittens plays selected
+ `tmyt -da kittens` searches for kittens downloads audio of selected
+ `tmyt -v` to go directly to the history
+ `tmyt -c` to go directly to channels
+ channels added by editing ~/.tmyt/channels file. Each string should countain channel id and channel name separated by space. e.g. somechannel Channel name\n
+ To get whiptail colorscheme as shown on screenshot add following to your shell starting script (.bashrc .zshrc etc.)
`export NEWT\_COLORS='root=,black\
border=red,black\
title=red,black\
roottext=red,black\
window=red,black\
textbox=white,black\
compactbutton=white,black\
listbox=white,black\
actlistbox=black,white\
actsellistbox=black,red'`
