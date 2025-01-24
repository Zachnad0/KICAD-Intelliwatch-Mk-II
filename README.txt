Intelliwatch Mk II

=== Operational Features ===
Internet Connection Required:
	Update internal date & time (automatic, whenever connection established)
	Obtain and display current stock values (manual update request)
	(?? google API) Show next #n google calendar events (A/B scroll up/down)
	(?? do last if at all) Google tasks integration (manual update request)
	Show weather for next 24 hours, very simple (mode, A/B scroll left/right)

Functions & Software Modes:
	Toggle time 7-seg disp. by displaying no digits (mode, A/B key)
	"off-mode" of LCD display (just a mode, makes LCD LED pin switch by p-MOS)
	QMC5883L Compass Mode shows current heading (mode, A/B keys change inclination temporarily, but that is not saved)
	Resistance Measuring Mode!!! color bands as rectangles on LCD (mode, A/B shows raw/E12)
	Multimeter mode voltmeter and ammeter (mode)
	(?? SD-card reading must be used) Cat Picture Mode cycle through pics on SD card (mode, A/B change pic)
	Torch Mode (A/B key inc/dec brightness in 3 steps, auto turn off on mode change)
	(?? optional random extra) "matrix mode" (like cmatrix)
	X - (LATER VERSION) snapper card holder, and maybe deployer??? (mode, A/B extend/retract)

=== Main Specs ===
Supply voltage: 
	9V battery?
	or 2-4x 3.7V Li-ion rechargeable cells?
	>> Standard DC Barrel Jack << (can connect to any >7V supply effectively)
	This version will NOT include a full-bridge rectifier for AC charging/power

Visual Displays and Indicators:
	1.8'' TFT LCD display (I2C)
	4-digit 7-segment display (I2C)
	4x SMD LEDs in series with keyswitches
	1x 5mm LED to indicate power ON.

Controls:
	4x cherry-mx keyswitches (3x??? - maybe make A/B just one?)
	standard power switch