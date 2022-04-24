# MPV Android Argparser
Simple script that lets you pass aruments to mpv-android, without root access

# Installation
```
termux-setup-storage
curl -sL https://raw.githubusercontent.com/TheGlockMisc/mpv-android-argparse/master/mpv -o $PREFIX/bin/mpv
```
# Setup
- Open MPV android
- Click 3 Dots at the top
- Settings
- Advanced
- Edit mpv.conf
- And insert this `include="/storage/emulated/0/mpv/mpv.tmp"`
- Click "Save"
