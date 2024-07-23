# yt-dlp
## A template with a config file and some utility scripts.
> - Download the official yt-dlp releases [here](https://github.com/yt-dlp/yt-dlp/releases).
> - Download FFmpeg [here](https://ffmpeg.org/download.html).

### Contents
- `yt-dlp.conf`: Generic config file that sets where the downloads are to be saved and deactivates mtime.
- `ffmpeg.exe` and `ffmprobe.exe`: utilities that improve yt-dlp's functions. Only needed as executables in Windows; other operating systems should use the PATH to the FFmpeg installation, if correctly set up.
- `dlclip.bash`: Bash script to download clips, providing a valid link, clip start time and clip end time.
- `dlsong.bash`: Bash script to download songs, providing a valid link and sound format.

### Directory tree
```
yt-dlp
├── dlclip.bash
├── dlsong.bash
├── Downloads
├── ffmpeg.exe
├── ffprobe.exe
├── yt-dlp
└── yt-dlp.conf
```
