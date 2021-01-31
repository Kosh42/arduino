Fork of https://github.com/markphelan/arduino

Uses an RS485-TTL adaptor connected to serial port of ATMega328P to receive DMX data and trigger relays. 

Configurable with push buttons and an OLED screen to set DMX address, monitor channel status, etc. 

Relays connect to digital pins 8 to 1 (backwards for layout). 

Push buttons wire between ground and pins:
9 (up), 
11 (down), 
10 (set), 

I have badly hacked Mark's code having no knowledge on the Arduino IDE syntax. I think it should work with the 8 channels, but I'm aware I don't posses the skills for the status curcles of relays 5-8 to appear as circles (as the screen yous need to swtich 1-4 then 5-8 to fit them in).

To run on a PCB who's KiCAD designs are here: https://github.com/Kosh42/PCB-Designs

This includes a BOM.

WARNING: As yet this code is untested, as is the PCB. Proceed at your own risk.