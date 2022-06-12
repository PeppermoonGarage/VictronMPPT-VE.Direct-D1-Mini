I'm using a D1 Mini ESP8266 board using ESPHome to send data via WiFi to a MQTT broker.  Wire the D1 Mini connections GND and D7 to the VE.Direct port.

Use a voltmeter to double check, but the ground pin is on the right when looking at the Victron VE.Direct port.  The +5v pin is on the far left, but it does not have enough power available to really power anything like the D1 Mini.
Tx is right next to the +5V and Rx (not used here) is next to the ground.

The VE.Direct port is a JST 2.0mm PH 4-Pin connector.  I got 5 on eBay for under $2.

I have posted the yaml configuration file I'm using on this site that is used with HomeAssistant/ESPHome.
