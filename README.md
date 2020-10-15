# rofi-solarized-dark-darker

My rofi configuration file for usage with i3wm. Based on solarized but using black instead of gray, therefore darker. ;-)

<img src="preview.png"/>

# Installation

## Install rofi

On Debian/Ubuntu:

```
apt-get update
apt-get install rofi
```

## Clone this repo

```
git clone https://github.com/christopher-john-czettel/rofi-solarized-dark-darker/ ~/.config/rofi
```

## Add i3 bindings

Edit `~/.config/i3/config`:

```
# rofi launcher/switcher biding5                                                                                                                                                                    
bindsym Mod1+Tab exec rofi -show windowcd
bindsym $mod+Tab exec rofi -show window
bindsym $mod+Shift+d exec rofi -show ssh
bindsym $mod+r exec rofi -show run
bindsym $mod+space exec rofi -show combi
```

# Author

- [Christopher John CZETTEL](https://github.com/christopher-john-czettel/) (https://christopher-czettel.net)

# License

- GPLv3
