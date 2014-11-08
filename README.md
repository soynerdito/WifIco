WifIco
=======

Small hardware adapter for ESP8266. Purpose make it 5v compatible and breadboard friendly.

Idea is to provide a small board to allow connecting the ESP8266 ver ESP02 to a breadboard. It is kept small so the price is cheap. A small batch was ordered to oshpark and waiting for order to arrive to see if the idea works.

**Features:**
- Allow input of 5V
- Exposes 3.3V regulated
- Level shifter for RX and TX signals (can be connected directly to Arduino)
- Breadboard friendly pinout
- Minu usb connector on the bottom (*for 5v power input only*)

For normal use please solder a wire on resistors R0XXX. This resistors are just exposing the RST and CHPD pins to allow moding the board for firmware updates.

Board design or prototype was NOT DONE! Just drawed a few versions on Eagle and order a batch of 3 boards to see what happens.
Plan is to scatter parts and build one and see what happens.

Blog post about project:
http://www.element14.com/community/groups/open-source-hardware/blog/2014/11/08/esp8266-interface-board-on-its-way

OSHPark board images


![alt tag](https://github.com/soynerdito/WifiIco/raw/master/images/WifiIcoOSHPark_top.png)
![alt tag](https://github.com/soynerdito/WifiIco/raw/master/images/WifiIcoOSHPark_back.png)
