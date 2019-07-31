*** How to setup Wifi without HDMI on Raspberry Pi Zero W before first boot ***

If you want to boot your Raspberry Pi Zero W for the first time without need to configure wifi through video output from microHDMI you can use this information below.

Steps:

1. Record Raspbian image on SD card using Win32DiskImager (Windows) 
2. Change Wifi credentials information inside config file located in ~/files/wpa_supplicant.conf
3. Copy both files from ~/files/ folder to the main catalog on your SD card
4. Connect your Raspberry Pi Zero W to power supply

If everything went good you should be able to see your device automatically connected to your router (you can use nmap ping scan to see if new device showed up in network).




Cheers!
                _             
  __ _ _ _ __ _| |__ ___ __ _ 
 / _` | '_/ _` | '_ \___/ _` |
 \__, |_| \__,_|_.__/   \__,_|
 |___/                        


Adam Grabowski