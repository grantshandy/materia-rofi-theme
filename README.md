# materia-rofi-theme
This is a rofi theme based on the materia gtk theme (https://github.com/nana-4/materia-theme)

What it looks like:

![Materia Rofi Theme](https://i.imgur.com/V4DQyiE.png)

## Installation

Make sure you have rofi installed.

Distro | Package Name / Link
--- | ---
Arch Linux | `materia-gtk-theme`
Debian testing / unstable | `materia-gtk-theme`
Fedora | `materia-gtk-theme` from [@LaurentTreguier's Copr](https://copr.fedorainfracloud.org/coprs/tcg/themes)
Solus | `materia-gtk-theme`
Ubuntu 18.04 or later | `materia-gtk-theme`
Ubuntu 17.10 | `materia-gtk-theme` from [@igor-dyatlov's PPA](https://launchpad.net/~dyatlov-igor/+archive/ubuntu/materia-theme)

Next, copy the file into your themes directory.

```
git clone https://github.com/DefunctLizard/materia-rofi-theme.git
cd materia-rofi-theme
cp materia.rasi /usr/share/rofi/themes
```

## Execute the Theme
Just type:
```
rofi -show run -theme materia
```
