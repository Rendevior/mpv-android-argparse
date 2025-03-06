# MPV Android Argparser
Simple script that lets you pass arguments to mpv-android, without root access

# Installation
```
termux-setup-storage
curl -o "$PREFIX/bin/mpv" -sL https://raw.githubusercontent.com/Rendevior/mpv-android-argparse/master/mpv
chmod +x "$PREFIX/bin/mpv"
```
# Setup
- Open MPV android
- Click 3 Dots at the top
- Settings
- Advanced
- Edit mpv.conf
- And insert this `include="/storage/emulated/0/mpv/mpv.tmp.mp4"`
> [!NOTE]
> When setting up on `mpvkt` you must add `/storage/emulated/0/mpv` on `pick mpv configuration storage location`
- Click "Save"
# How to Run
Thats it:
```
mpv <video-url> <args>
```
