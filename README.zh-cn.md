# gozjaro-wallpapers

Gozjaro 官方壁纸（1920×1080，PNG）。4 组 × 亮/暗各一张：

- `emblem` — 狗头徽记
- `peaks` — 雪山 + 极光
- `ribbons` — 丝带（浅色）
- `dusk` — 城市黄昏

## 安装布局（gozpak 配方 / 手工安装）

```
/usr/share/backgrounds/gozjaro/gozjaro-*.png      # 壁纸本体（Xfce/GTK 直接读这里）
/usr/share/gnome-background-properties/gozjaro.xml # GNOME（本仓 gnome/）
/usr/share/wallpapers/Gozjaro/                     # KDE（本仓 kde/Gozjaro/，
                                                   # 安装时把 PNG 拷进 contents/images/）
```

各 DE 的默认指向：GNOME 装 xml 即在"背景"里出现；KDE 装到 /usr/share/wallpapers/ 即被 Plasma 识别；
Xfce/其他 DE 用文件管理器或 xfconf 指到 /usr/share/backgrounds/gozjaro/ 即可。

License: MIT

[English](README.md)
