## i3 config

### i3wm configuration for Kali Linux Xfce 

#### Config Version: 3.13
#### i3 version: 4.13 
#### Author: Brainfuck




#### INSTALLATION

##### Install i3 with dependencies:
```bash
sudo apt-get update && sudo apt-get dist-upgrade -y
sudo apt-get install -y i3 i3blocks scrot feh xfonts-terminus ttf-liberation
```



#### CONFIGURATION

##### FontAwesome for i3-bar:
Download --> http://fontawesome.io/

```bash
mkdir -v ~/.local/share/fonts
cp fontawesome-webfont.ttf ~/.local/share/fonts
fc-cache -fv
```


##### Simply run this commands:
```bash
cd i3-config/
cp -R i3 ~/.config 
cp -R gtk-3.0 ~/.config
mv gtkrc-2.0 .gtkrc2-0 
cp .gtkrc-2.0 $HOME
```


##### GTK Theme & Icons:

GTK3 Theme --> Arc-Dark: https://github.com/horst3180/arc-theme

Icons Theme --> Arc-Icon-Theme: https://github.com/horst3180/arc-icon-theme




**Kali Linux - Xfce**

![alt text](http://i.hizliresim.com/g2YvXR.png)


**Kali Linux - i3wm**
![alt text](http://i.hizliresim.com/Qvz8vk.png)
