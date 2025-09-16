# Gnome Theme Continuity

> A simple script to set the theme of the Gnome Desktop in GTK3, GTK4, Qt5 and Qt6, this also will fix Flatpaks theming.

## What Do?

This script is for fixing the continuity errors on Gnome Desktop, it will guide you through setting all the fiddly bits for updating your theme, including but not limited to... 

- `prefers-dark` Setting
- GTK3 Theme
- GTK4 Theme
- Adwaita to use your theme's stylesheet
- Flatpaks to use your theme's stylesheet
- QT to use your Adwaita Stylesheet

## How start?

### Dependencies

These scripts rely on a few cli tools to be preinstalled on your system:

- Gnome 40+ (tested on Fedora Workstation 42)
- [Python 3](https://www.python.org/downloads/)

### Get the repo and move into the directory
```sh
git clone https://github.com/mowglixx/gno-problemo.git
cd gno-problemo
```

### Copy the scripts to a PATH location of your choice
#### Default: '~/.local/bin/'
```sh
cp gno-problemo ~/.local/bin/
```

### Go to said location and make the script executable
```sh
chmod +x ~/.local/bin/gno-problemo
```
