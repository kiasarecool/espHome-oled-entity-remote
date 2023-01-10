# espHome-oled-entity-remote
espHome oled entity remote
A simple espHome "remote" for controlling entitys 
either directly with service calls from esp device
or by using home assistant automations tied to each button
*to use automations instead of service calls requires section to
be commented out and set hide_buttons_in_ha to false

To use this just copy and paste this yaml into the config of a new esphome ESP32 device 
and edit the substutions 
reccomended to copy existing config into a txt file to avoid losing the board type
and encryption / ota keys
