# domoticz.plugin.ioplus
Domoticz plugin for IOplus 8 relay board on raspberry
https://sequentmicrosystems.com/product/raspberry-pi-home-automation-card/

INSTALL:
* cd ~/domoticz/plugins
* git clone https://github.com/josefpavlik/domoticz.plugin.ioplus.git
* sudo apt install python3-rpi.gpio python3-smbus 
* sudo service domoticz restart

SETUP:
Go to the Hardware menu and create new hardware of type "Raspberry IOplus". Set the board id. 
Devices will be created automatically.
There are devices Relay_1 to Relay_8 and Input_1 to Input_8.
Currently only relays and opto isolated inputs are supported.


