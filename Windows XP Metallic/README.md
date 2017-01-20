Windows 10 is a theme made to simulate in the closest way the world-known OS.
For the moment, this theme works with the following Desktop environments : 
- Cinnamon 2.4/2.6
- GNOME-SHELL 3.14/3.16/3.18
- XFCE 4
- MATE 1.8
- LXDE 0.8 (part)
- KDE Plasma 5 (KDE 4 has some issues)
- Unity 7


### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Windows\ XP\ Luna"
gsettings set org.gnome.desktop.wm.preferences theme "Windows\ XP\ Luna"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Windows\ XP\ Luna"
xfconf-query -c xfwm4 -p /general/theme -s "Windows\ XP\ Luna"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### Code and license

License: GPL-3.0+
