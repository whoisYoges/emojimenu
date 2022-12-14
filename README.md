# emojimenu

Search, copy and insert any emoji by name using dmenu/rofi.

# Dependencies

- dmenu with color emoji support
- cut
- sed
- xclip
- xdotool

### Optional Dependencies
- rofi
- libnotify

# Installation and Usage

## Arch and arch based systems

Use your favourite aur helper (eg: yay) and install [emojimenu](https://aur.archlinux.org/packages/emojimenu) from aur.

```
yay -S emojimenu
```

## From Source

```
curl -LOS "https://raw.githubusercontent.com/whoisYoges/emojimenu/master/allemojis.txt"
curl -LOS "https://raw.githubusercontent.com/whoisYoges/emojimenu/master/emojimenu"
chmod +x emojimenu
sudo mkdir -p /usr/share/emojimenu
sudo mv allemojis.txt /usr/share/emojimenu/allemojis.txt
sudo mv emojimenu /usr/local/bin/emojimenu
```

# Uninstallation

```
sudo rm /usr/share/emojimenu/allemojis.txt /usr/local/bin/emojimenu
```

# FAQ

Having trouble with color emoji support enabled dmenu?  
Checkout my build at <https://github.com/whoisYoges/dmenu>.
