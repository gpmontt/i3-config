## i3 config

### Config for i3 - Tiling Window Manager

#### Config Version: 3.9
#### i3 version: 4.12 
#### Author: Brainfuck
#### Tested on Kali Linu8x Xfce

![alt text](http://i.hizliresim.com/B8WJaM.png)




#### INSTALL
```bash
sudo apt-get install -y i3 i3-wm 
sudo apt-get install -y scrot 
sudo apt-get install -y feh
sudo apt-get install -y xfonts-terminus
sudo apt-get install -y ttf-liberation 
```

#### CONFIGURATION

Edit the files: i3/config, gtk-3.0/settings.ini and gtkrc-2.0 with your preferences

Copy the folders i3 and gtk-3.0 to $HOME/.config directory   

Rename the file gtkrc-2.0 to ".gtkrc-2.0" then move it to $HOME directory


This is the correct structure of the files and folders
```
$HOME/.gtkrc-2.0
$HOME/.config/i3
$HOME/.config/gtk-3.0
```


GTK3 Theme --> Adwaita-Xfce: https://github.com/thearakattack/adwaita-xfce

Icons Theme --> Paper: https://github.com/snwh/paper-icon-theme

Terminal Fonts --> Terminus 12 (see bashrc)
