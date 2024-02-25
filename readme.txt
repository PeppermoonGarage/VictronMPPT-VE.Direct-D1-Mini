I'm using a D1 Mini ESP8266 board using ESPHome to send data via WiFi to a MQTT broker. Wire the D1 Mini connections GND and D7 to the VE.Direct port pins GND and TX.

Use a voltmeter to double check, but the ground pin is on the right when looking at the Victron VE.Direct port. The +5v pin is on the far left, but it does not have enough power available to really power anything like the D1 Mini. TX is right next to the +5V and RX (not used here) is next to the ground. So VE.Direct TX to D1-Mini D7 and VE.Direct GND to D1-Mini GND

From Victron: How much current can I draw from the power pin in the VE.Direct port?  Max 10mA average, with max 20mA/5ms bursts.

The VE.Direct port is a JST 2.0mm PH 4-Pin connector. I got 5 on eBay for under $2.

I have posted the yaml configuration file I'm using on this site that is used with HomeAssistant/ESPHome. Note that I have code in there for a display shield that is optional.

I stacked the D1 Mini, an OLED display shield, and a power shield for my build.
