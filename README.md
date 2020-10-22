# 6522-6526-kernal-switcher
Adaptation of Sven Petersen's Keyboard Kernal Switch for MOS6522 or MOS6526 (VIC-20, C64, C128)

An ATMEGA328P microcontroller connected to the keyboard wires to listen for changes to keypresses 
of most of the top row of the keyboard. Hold down a number key and press RESTORE, (VIC-20 has 
limited compatibility) and three output bits (A B & C) for system control can be toggled by code.
The LED and bottom jumper can be wired directly (behind the resistor from the LED pin for example) 
and reprogrammed to use those as two extra output bits. Inputs can be reprogrammed to include + 
and - for example and then increase/decrease the selected output to control multiple EPROMs or 
devices for different reboot modes.  Memory controller modes, other ROMs, better control over more 
function roms in a C128 with more KERNAL ROMs (2 and 4 or 4 and 2 work well together with just ABC)
or memory maps etc.  With 5 you can dedicate 2 and 3 (giving 4 and 8 selections) instead of sharing 
lines as demonstrated in the C128 installation.
