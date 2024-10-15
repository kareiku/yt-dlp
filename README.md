# yt-dlp
## A template with a config file and some utility scripts.
- Download the official yt-dlp releases [here](https://github.com/yt-dlp/yt-dlp/releases).
- Download FFmpeg [here](https://ffmpeg.org/download.html).

### Contents
- `dlclip.bash`: bash script to download clips, providing a valid link, clip start time and clip end time.
- `dlsong.bash`: bash script to download songs, providing a valid link and sound format.
- `Downloads`: subdirectory used to save the downloaded files.
- `ffmpeg.exe` and `ffmprobe.exe`: utilities that allow or improve yt-dlp's functions. Only needed as executables in Windows; other operating systems should use the PATH to the FFmpeg installation, if correctly set up.
- `yt-dlp.conf`: generic config file that sets where the downloads are to be saved and deactivates mtime.
- `yt-dlp.exe`: app's main executable. Runnable from the system's terminal, each OS has their own compiled file. Can be found on the official yt-dlp releases repository page.

### Directory tree
```
yt-dlp
├── dlclip.bash
├── dlsong.bash
├── Downloads
├── ffmpeg.exe
├── ffprobe.exe
├── yt-dlp.conf
└── yt-dlp.exe
```
