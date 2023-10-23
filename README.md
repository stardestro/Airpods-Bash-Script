# Bluetooth Bash Script
This is a script I made to connect and disconnect from my airpods using the terminal rather than clicking 5 times to navigate the GUI on Ubuntu
# How to use
1. Figure out your bluetooth devices MAC address
2. Replace 00:00:00:00:00:00 with your devices mac address
3. (optional) rename the script to what ever you want the commandname to be
4. Place within /usr/bin
   
### Quick commands:

Use to find the MAC address of all connected bluetooth devices
```
hcitool con
```
Incase the script doesn't have system permission to run
```
chmod +x airpod
```
To copy the file to the /usr/bin
```
sudo cp airpod /usr/bin/
```
*This has been tested for Ubuntu 22.04.3 LTS
