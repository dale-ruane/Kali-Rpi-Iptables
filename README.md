Kali-Rpi-Iptables
=================
This is a recompiled version of Kali Linux for the Raspberry Pi including IPTables. 

I recently realised that the arm version of Kali linux, specifically for the Raspberry Pi, was lacking IPTables.

I decided to set about adding IPTables into the kernel and then providing an image that would include IPTables by default.



To install:
============

If you just wish to install the kernel, place the kernel.img from the /kernel/ directory on this git inside of your /boot/
partition.

If you want to use the whole image file simply download the latest version from this git and use DD to put it on your SD card.

eg.

dd if=/path/to/kali.img of=/path/to/sdcard

(This process can take a while)
