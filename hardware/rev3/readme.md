# Preliminary Files for rev3

Untested! 

Changes:
* Changed Buffer to N-Fet-Buffer 
* Moved datapin to GPIO 14
	* Data-In is no more switchable via resistor 
* Power rail switch to 5V
* rev 3 uses foloowing Pins of tinyPico
	* GND (both are connected - you an use one or both)
	* 3V3 as lower voltage level for level shifter 
	+ 5V as supply voltage for LEDs 
	* GPIO14 data signal for LEDs (needs to be same voltage level as on 3.3V Pin) 
