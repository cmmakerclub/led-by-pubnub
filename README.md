led-by-pubnub
=========================

Connect Led to computer (eg. raspberry pi).


Install
===

	npm install pubnub serialport


Setup
===

Set port to led_pubnub.js at 

	var serialPort = new SerialPort("[YOUR PORT]", {
		
eg. /dev/ttyUSB0

Find port

	ls /dev/tty*
	
PUBNUB
===

set publish\_key, subscribe\_key , channel

In this we set 

	publish_key   : "demo"
	subscribe_key : "demo"
	channel       : lightme
	
	
---
For Chiang Mai maker club

led revice text as hex eg #333fff
