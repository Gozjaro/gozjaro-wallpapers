# gozjaro-wallpapers

Official Gozjaro wallpapers (1920×1080, PNG). 4 sets, light/dark each:

- `emblem` — the gozjaro dog-head mark
- `peaks` — snowy peaks with pink/blue aurora
- `ribbons` — ribbons (light theme)
- `dusk` — city at dusk

## Install layout (gozpak recipe / manual)

```
/usr/share/backgrounds/gozjaro/gozjaro-*.png      # the wallpapers (Xfce/GTK read this dir)
/usr/share/gnome-background-properties/gozjaro.xml # GNOME (this repo's gnome/)
/usr/share/wallpapers/Gozjaro/                     # KDE (this repo's kde/Gozjaro/,
                                                   # recipe copies the PNGs into contents/images/)
```

Per-DE defaults: GNOME picks the xml up in Background settings once installed; KDE/Plasma recognizes
anything under /usr/share/wallpapers/; on Xfce and other DEs point the file manager or xfconf
channel at /usr/share/backgrounds/gozjaro/.

License: MIT

[简体中文](README.zh-cn.md)
