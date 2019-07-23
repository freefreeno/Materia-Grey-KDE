
Materia Grey KDE - This is a grey port of the popular [Materia KDE](https://github.com/PapirusDevelopmentTeam/materia-kde) for Plasma 5 desktop with a few additions and extras. 

In this repository you'll find:
- Two sets of folder icons
- Konsole Color Scheme
- Plasma Color Scheme
- Plasma Desktop Theme
- Plasma Look-and-Feel Settings
- Materia Grey GTK Theme made specifically for KDE.


## Recommendations

- Install [Papirus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for a more consistent and beautiful experience.

- Set tree menu view for systemsettings

- On systemsettings set **Noto Sans** font for title, menu and toolbar

- For better looking use toolbar icons without text with 16px size (for Papirus themes)

- For Materia Blur enable translucency and blur effects on KDE sytemsettings. Set value 5 for noise and blur strengths on blur effect settings.

- Recommended software for better experience with Materia Blur: Dolphin, Ark, Kate,Falkon, Konsole

## Hacks for small screen resolution

- Install widgets [Active Window Control](https://github.com/kotelnik/plasma-applet-active-window-control) & [Application Menu](https://cgit.kde.org/plasma-workspace.git/tree/applets/appmenu) and move to panel
- Disable window buttons & titlebar on decoration:

open rc-file on aurorae theme and set:
```
ButtonHeight=0
ButtonWidth=0
TitleHeight=0
TitleEdgeTop=0
```
- Use [GTK3-noCSD](https://github.com/PCMan/gtk3-nocsd) script 

## Known issues

- Old version qBittorrent (~3.3.1) not used 22px icon size on toolbar (icons will be blurred, update to fresh version for solve this)

- On some propietary video drivers Aurorae have wrong rendering by default with Materia theme. For fix that use this config on ~/.Xresources:

```
Xft.dpi:       96
Xft.antialias: true
Xft.hinting:   true
Xft.autohint:  false
Xft.hintstyle: hintslight
Xft.lcdfilter: lcddefault
Xft.rgba:      rgb 
```

## License

GNU GPL v3

The original Materia KDE theme is here:
https://store.kde.org/p/1229162

or here

https://github.com/PapirusDevelopmentTeam/materia-kde
# Materia-Grey-KDE
