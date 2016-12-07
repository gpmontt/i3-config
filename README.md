## i3 config

### i3wm configuration for Kali Linux Xfce 

#### Config Version: 3.12
#### i3 version: 4.13 
#### Author: Brainfuck

![alt text](http://i.hizliresim.com/g2yzg3.png)




#### INSTALL
```bash
sudo apt-get update && sudo apt-get dist-upgrade 
sudo apt-get install i3 i3-wm scrot feh xfonts-terminus ttf-liberation
```

#### CONFIGURATION

Edit "i3/config" as you like  

Edit "gtk-3.0/settings.ini" and "gtkrc-2.0" with your name of your theme and icons (see the file included)

Copy the folders "i3" and "gtk-3.0" to $HOME/.config directory   

Rename the file "gtkrc-2.0" to ".gtkrc-2.0" then move it to $HOME directory

If you want the bash prompt like the screenshot, read bashrc file. 


This is the correct structure of the files and folders when you have finished
```
$HOME/.gtkrc-2.0
$HOME/.config/i3
$HOME/.config/gtk-3.0
```

Resources:

GTK3 Theme --> Arc-Grey-Dark: https://github.com/eti0/arc-grey-theme

Icons Theme --> Faenza-Grey: http://riverraiden.deviantart.com/art/Faenza-Grey-264713552

