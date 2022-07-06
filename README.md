# tmyt
**Terminal youtube client**

Small script to select videos in terminal and watch them with mpv.

<img src="screenshot.png" alt="drawing" width="700" align="center" />

**Features**
+ Choose video quality
+ Download/watch videos

**Dependencies**
+ whiptail
+ mpv (for watchling online)
+ yt-dlp (for downloading)

**Installation**
+ `$wget https://raw.githubusercontent.com/tzrn/tmyt/main/tmyt`
+ `#ln -s /absolute/path\ to/tmyt /bin/tmyt`

**Usage**
+ `tmyt p search+query` to play video
+ `tmyt d search+query` to download video
+ choose video and quality
