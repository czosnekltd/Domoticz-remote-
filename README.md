Domoticz Esp8266 + Nextion Remote 

<img width="100%" alt="esp8266 + Nextion Schematic" src="https://github.com/ledfreak3d/Domoticz-remote-/blob/master/git.jpg">

Using a Nextion 3.5 inch display and a Esp8266 to controll virtial switches in Domoticz and read data back.

Currently this firmware can controll switches and Dimmers
And will report the battery status of the remote back to domoticz for monitoring.

Please keep in mind this is still a work in progress 

page added free for anybody to use

but pleade if any improvements are made please share them with the community !!!!!!


Nextion Graphics file the photoshop template and the arduino code are all provided 

The firmware uses wifi manager to connect to the wifi network the first time 
Once ota update is enabled on the display.
The esp will host a web server on its ip where you can upload a new firmware file to.
Please keep in mind please compile the firmware with sufficiant file storage so it can actualy save the field for flashing later on
------------------------------------------------------------------------------------------------------------------------------------
Update !!!!!!!! 

Idx config can be done via web interface now
all settings are now saved in a json config file
this file can also be uploaded to the esp via the build in ftp server now.


