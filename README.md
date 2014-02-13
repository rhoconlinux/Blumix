Blumix Gtk3.10 
======

**Blumix Gtk Theme: Simple. Clean. Essential.** Started as a minimal Blue-ish Mod for Numix Gtk3 Theme, now, with some perspective, it's growing with its own identity. Supported for gtk3.10, gtk3.6, gtk2and metacity3. :)

![alt tag](http://)


Install it:
-----------
### **Manual: **
Download the file from here, deviant-art or gnome-look. Uncompress the stuff. Browse the uncompressed content and copy the folder named Blumix in /usr/share/themes (*this will require root access*). Apply it with your favourite tunning tool (gnome-tweaks, unity-tweak, ubuntu-tweak... etc.).

#### **Ninja Install** (yeah): 
just copy-paste this line in your terminal. Press <kbd>Enter</kbd>. Magic will happen. 

```
mkdir -p ~/blumix-install && cd ~/blumix-install && wget https://github.com/rhoconlinux/Blumix/archive/master.zip && unzip master.zip && cd Blumix-master && sudo cp -a Blumix /usr/share/themes/Blumix1.0 && gsettings set org.gnome.desktop.interface gtk-theme "Blumix1.0" && cd ~ && rm -R ~/blumix-install/
```
Screenshots:
-----------


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
- 
-** Nautilus:** complete rework. Now it is minimal. But really minimal. (oh!... and usable too!). :)   

-  **New dependences. **It now requires an additional engine to draw pixmaps (besides murrine). In ubuntu, run in a terminal the following line in order to install it: `sudo apt-get install -y gtk2-engines-murrine  gtk2-engines-pixbuf` 


Check more info on my blog. Oh, and use google translate if you are not an spanish speaker. :P 







- - -

OLD STUFF:

*Changelog V0.5 [Dec. 2013]* 
More in:
http://rhoconlinux.wordpress.com/2013/11/10/blumix-mod-de-numix-celestito/

· New Gtk2 theme, completely reworked:
	-scrollbars
	-buttons distance
	-check buttons
	-spacing on selected items
	-New menubars matching the theme
	-...all that now is coherent with the gtk3 version. 

· New GTk3 menuitem select instance
· Fixed GTk3 all the buttons and isntances with slightly rounded borders (to be continued in nautilus)
· Dark-Theme mode taken out. No further support for this is spected. 
· Bunch of other minor fixes

To-do:
This project is reaching it's first major release, with all the features about to be implemented. It still lacks work on:
Terminal scrollbars
New default Window Border
Alternative Window Borders


*Changelog V0.2 [Nov. 2013]* 

· New colored buttons and SVG assets of the theme 

· New GTk2 theme

· New menu bar, light colored

· New Dark-Theme mode

· Bunch of other minor fixes


