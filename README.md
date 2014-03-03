Blumix Gtk3.10 
======

**Blumix Gtk Theme: Simple. Rounded. Essential.** Started as a minimal Blue-ish Mod for Numix Gtk3 Theme, now, with some perspective, it's growing with its own identity. It supports gtk3.10, gtk3.6, gtk2and metacity3. :)

![alt tag](http://rhoconlinux.files.wordpress.com/2014/02/banner-final.png)


Install it:
-----------


## Ninja Install (yeah): 
just copy-paste this line in your terminal. Press <kbd>Enter</kbd>. Magic will happen. 
*(It will ask for super-user permissions to copy the theme in /usr/share/themes)*

```
mkdir -p ~/blumix-install && cd ~/blumix-install && wget https://github.com/rhoconlinux/Blumix/archive/master.zip && unzip master.zip && cd Blumix-master && sudo rm -Rf --force /usr/share/themes/Blumix1.0/ && sudo cp -a Blumix /usr/share/themes/Blumix1.0 && gsettings set org.gnome.desktop.interface gtk-theme "Blumix1.0" &&  gsettings set org.gnome.desktop.wm.preferences theme 'Blumix1.0' && cd ~ && rm -R ~/blumix-install/

```

<br>
<br>

| Note |
|--------|
|Please note that **this theme _will require_ murrine, pixbuf and unico engines installed** on your system. If you don't have them, Firefox, Thunderbird, Libreoffice and other gtk2 programs won't draw the theme (and you'll get a win95 look).To install the requiried packages in Ubuntu and derivatives, run: 
|`sudo apt-get install -y gtk2-engines-murrine gtk2-engines-pixbuf gtk3-engines-unico`


<br>
<br>


### Manual install:
Download the file from [here](https://github.com/rhoconlinux/Blumix/archive/master.zip) (or click on the "download" button on the right sidebar). Once you got the file, uncompress the zip. Browse the uncompressed content and copy the folder named **Blumix (not *blumix-master*!)** in */usr/share/themes/* (*this will require root access*). Apply it with your favourite tunning tool (gnome-tweaks, unity-tweak, ubuntu-tweak... etc.). If you can't see properly some apps read the note above... probably you should install the required engines to make it work. You can also pass by and give a like in deviant-art and gnome-look if you feel so. If you see anything odd, please report a bug or drop a comment in [my blog](https://rhoconlinux.wordpress.com/2014/02/13/blumix-1-0-actualizado-el-tema-gtk3-10-minimalismo-nuevo/). 

<br>
<br>





  
Screenshots:
-----------
Full Review and Screenshots [here](http://rhoconlinux.wordpress.com/2014/02/13/blumix-1-0-actualizado-el-tema-gtk3-10-minimalismo-nuevo/) *(in spanish)*

![Collage](http://rhoconlinux.files.wordpress.com/2014/02/collage.png)



What's new:
-----------

Changelog **V1.0** (yey!) [Feb. 2014]

- **New revisited Gtk3 theme:** Now focused on gtk3.10 *(no further development for previous gtk versions -3.6, 3.8-, sorry)*. New toolbars, Headerbars, Buttons, new buttons-headers-indicators-checks rounding (all over to gain coherence), new neat scrollbars, fixed distances, early version of animations. Several detail focused fixes.
- **New Gtk2 theme, massively reworked:**  *scrollbars
	*buttons focus
	*separators (now are transparent! ^_^)
	*Handlers (Transparent)
	*Incresed integration 
	*Libreoffice integration
	*Menu-button policy
	*Use of pixmap to force fixing some stuff
- **New Window Borders:** Focused (unfocused) effect, rounding, lateral borders fix, new buttons, elements ported to svg.
- First granite wigets integration (Elementary OS). New tabs, colors and stuff. :P
- Nautilus: complete rework. Now it is minimal. But really minimal. (oh!... and usable too!). :)   

-  **New dependences. **It now requires an additional engine to draw pixmaps (besides murrine). In ubuntu, run in a terminal the following line in order to install it: `sudo apt-get install -y gtk2-engines-murrine  gtk2-engines-pixbuf` 


Check more info on [my blog](http://rhoconlinux.wordpress.com). Oh, and use google translate if you are not an spanish speaker. :P 











