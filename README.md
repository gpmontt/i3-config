## i3 config

### i3wm configuration for Kali Linux Xfce 

#### Config Version: 3.30
#### i3 version: 4.13 
#### Author: Brainfuck




#### INSTALLATION

##### Install i3 with dependencies:
```bash
sudo apt-get update && sudo apt-get dist-upgrade -y
sudo apt-get install -y i3 i3blocks rofi scrot feh compton ranger lxappearance xfonts-terminus ttf-liberation
```



#### CONFIGURATION

##### Run this commands for the main part of the configuration (i3, rofi and compton):
```bash
cd i3-config/
cp -R i3 ~/.config
cp -R rofi ~/.config
cp compton.conf ~/.config
```


##### Ranger File Manager:

After startup, ranger creates a directory ~/.config/ranger. To copy the default configuration to this directory issue the following command: 

```bash
ranger --copy-config=all
```

ranger official wiki --> https://github.com/ranger/ranger/wiki/Official-user-guide


##### FontAwesome for i3-bar:
Download --> http://fontawesome.io/

```bash
mkdir -v ~/.local/share/fonts
cp fontawesome-webfont.ttf ~/.local/share/fonts
fc-cache -fv
```



#### THEMING

##### GTK Theme & Icons:

Download GTK and Icons themes:

GTK3 Theme --> Arc-Dark: https://github.com/horst3180/arc-theme

Icons Theme --> Arc-Icon-Theme: https://github.com/horst3180/arc-icon-theme

You can also download GTK Arc-Theme from apt:

```bash
sudo apt-get install arc-theme
```

Then select gtk theme and icons from "lxappearance" menu'


##### Rofi Theme:

Arc-Dark --> https://github.com/leofa/rofi-themes




**Kali Linux - i3wm**
![alt text](https://i.hizliresim.com/MvdMmM.png)


**Kali Linux - Xfce**

![alt text](https://i.hizliresim.com/vpj386.png)
