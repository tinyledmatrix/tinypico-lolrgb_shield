# Preliminary Files for rev2

DO NOT USE THIS REVISON. POWERING ALL LEDs FROM THE 3.3V LDO COULD BE PROBLEMATIC!
USE REV3! 

Changes:
* Removed Buffer vor data
* Moved datapin to GPIO 14
	* Data-Oin is nomre switchable via resistor 
* Power rail switch to 3.3V
	* No 5V Power needed anymore
* rev 2 ses foloowing Pins of tinyPico
	* GND (both are connected - youse one or both)
	* 3V3 as supolly voltage for LEDS. (if not used if tinyPico you could also suplly 5V here)
	* GPIO14 data signal for LEDs (neds to be same voltage level as suplly 
