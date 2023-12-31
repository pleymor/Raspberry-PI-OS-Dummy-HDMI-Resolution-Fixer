# Raspberry-PI-OS-Dummy-HDMI-Resolution-Fixer
Set Full HD resolution when plugging Dummy HDMI dongle to a Raspberry PI on Raspberry PI OS (useful for VNC or teamviewer on a device with no monitor)

````sh
sudo cp 91_custom_xrandr /etc/X11/Xsession.d/
./hdmi_fullhd.sh
````

Then open Start menu, Preferences, Screen Configuration
Right clisk on the screen, Resolution, select another one, apply, refuse reboot
The select the resolution 1920x1080, Apply, reboot.
You should have the desired resolution now :)
