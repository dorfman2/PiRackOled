# PiRack OLED Script
This script is based on Adafruit's OLED script, but has been modified to use a 128x64 OLED and a pushbutton.
It's designed to be used with a raspberry pi server rack.

## Running Stats on Boot

You can pretty easily make it so this handy program runs every time you boot your Pi.

The fastest/easiest way is to put it in `/etc/rc.local`

Run `sudo nano /etc/rc.local` and add the line

`sudo python3 /home/pi/stats.py &`

on its own line right before exit 0

Then save and exit. Reboot to verify that the screen comes up on boot!

## Useful Links
https://learn.adafruit.com/adafruit-pioled-128x32-mini-oled-for-raspberry-pi/usage
https://www.thingiverse.com/thing:3362054