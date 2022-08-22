## Turning a Chromebook into a Linux Box

Hello everyone, welcome to the first post on my blog. I was inspired to write this blog after recently turning an old Chromebook I had into a Linux box.
Here I will document what I did to turn it into a full working Linux Box.
### Setup
First of all, the Chromebook I used was an Acer Chromebook R11. It reached its End of Life fairly recently and stopped receiving updates, so I wanted to add Linux to it so it was still usable.
I also used a USB drive for booting the Linux distros.

First of all, I turned on Developer Mode. Note: This will wipe all data on the Chromebook. To do this, I:
1. Press escape, refresh and power at the same time.
2. Press Ctrl+D when a message pops up for inserting a recovery stick.
3. Wait a while for it to reboot.

Developer Mode was now turned on. Next, I used [Mr Chromeboxes Firmware Utility Script](https://mrchromebox.tech/#fwscript) to install RW Legacy Firmware.

Once RW Legacy Firmware is installed, you can press Ctrl+L on the boot screen to boot from a USB. This is how I installed Linux.

### Different Distros
Now that I was able to boot from a USB, I tried a few different Linux distros. The first was GalliumOS which is advertised for this very purpose. 
However, it hasn't been updated since 2019, and I wanted a distribution which was staying updated. I next tried Mint, which is the OS I use on my main computer, but XFCE does not work great which my touchscreen (and I wanted to be able to use my Chromebook as a tablet).
I finally settled on Pop OS, which uses GNOME. This currently works great, if it's sometimes a little slow.

### Customizations
Finally, I setup hotkeys and such for the keys at the top of the keyboard (like Volume, Brightness, etc.). By default, these buttons are bound to the F keys.
Volume Up, Down, Mute, and Fullscreen I simply set using GNOME's keyboard shortcuts. For brightness, I used [this script](https://askubuntu.com/questions/899821/control-monitor-brightness-with-keyboard-shortcut).

### Final Thoughts
I hope this was somewhat informational. Since I didn't change the firmware, at every boot the Chromebook still displays the Developer Mode screen. Additionally, if you plan to do this, you might want an SD card if your Chromebook has a small hard drive like mine (16 GB).
Overall, this process worked really well, and I may update this with new information if I get any. Thanks for reading!
