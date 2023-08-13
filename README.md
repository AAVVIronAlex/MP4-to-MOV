# MP4toMOV

This shell script lets the user convert their .mp4 video files to .mov video files.

## Usecases

BlackMagic's DaVinci Resolve does not have support for .mp4 files on Linux, so this might come in handy if someone plans to edit videos with DaVinci Resolve on Linux.

## How to use

Download or clone and then go the .sh file to the directory your video is stored in, use the `cd` command to do that. When at the location in the termninal simply type `./mp4_to_mov_converter.sh` in the terminal. 

This might take some time depending on the speed of your computer.

After the video has been converted it will appear in the folder called `transcoded` in the same directory as the `./mp4_to_mov_converter.sh` file is. 

## Requirements

To run this shell script you will need the `ffmpeg` terminal program.

If you do not have `ffmpeg` installed you will have to download it.

### Downloading and installing `ffmpeg` on Debian based distributions

Update your repositories.

`sudo apt update`

Install `ffmpeg`.

`sudo apt install ffmpeg`

Verify installation.

`ffmpeg -version`

### Downloading and installing `ffmpeg` on Arch based distributions (using pacman)

Update your repositories.

`pacman -Syu`

Install `ffmpeg`.

`pacman -S ffmpeg`

Verify installation

`ffmpeg --version`

### Downloading and installing `ffmpeg` on Gentoo

https://wiki.gentoo.org/wiki/FFmpeg#Installation