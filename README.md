## i3config - i3wm configuration for Kali Linux


### Installation

#### Install i3 with dependencies:
```bash
sudo apt-get update && sudo apt-get dist-upgrade -y
sudo apt-get install -y i3 rofi scrot feh compton ranger lxappearance xfonts-terminus
```

#### Install i3blocks from github:
```bash
git clone git://github.com/vivien/i3blocks
cd i3blocks
make clean debug # or make clean all
make install
```

### Configuration

#### Run this commands (i3, rofi and compton settings):
```bash
cd i3-config/
cp -R i3 ~/.config
cp -R rofi ~/.config
cp compton.conf ~/.config
```

#### Ranger File Manager:

After startup, ranger creates a directory ~/.config/ranger. To copy the default configuration to this directory issue the following command:

```bash
ranger --copy-config=all
```

ranger official wiki --> https://github.com/ranger/ranger/wiki/Official-user-guide

### Theming

#### GTK Theme & Icons:

Download GTK and Icons themes:

GTK3 Theme --> Arc-Dark: https://github.com/horst3180/arc-theme

Icons Theme --> Arc-Icon-Theme: https://github.com/horst3180/arc-icon-theme

You can also download GTK Arc-Theme from apt:

```bash
sudo apt-get install arc-theme
```

Then select gtk theme and icons from "lxappearance" menu'

#### Rofi Theme:

Arc-Dark --> https://github.com/leofa/rofi-themes

### Fonts settings

#### FontAwesome for i3-blocks icons:
Download --> http://fontawesome.io/

```bash
mkdir -v ~/.local/share/fonts
cp fontawesome-webfont.ttf ~/.local/share/fonts
fc-cache -fv
```

#### Terminal and i3blocks fonts:

Fonts in the images are [ohsnap](https://sourceforge.net/projects/osnapfont) for i3blocks and [Tamsyn](http://www.fial.com/~scott/tamsyn-font) for terminal.

On Debian systems the "bitmap fonts" must be enabled.
Read the instructions here:

https://forums.bunsenlabs.org/viewtopic.php?id=1473

for [fonts.conf](https://manpages.debian.org/jessie/fontconfig-config/fonts-conf.5.en.html) file, the correct systax is this:

https://superuser.com/questions/116859/font-substitution-with-fonts-conf

#### Screenshots:

**Kali Linux - i3wm**
![alt text](https://i.hizliresim.com/XXVdD6.png)

**Kali Linux - Xfce**

![alt text](https://i.hizliresim.com/8dq89V.png)
