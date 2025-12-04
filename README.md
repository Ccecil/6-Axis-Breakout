6 Axis Breakout

This is a breakout board designed to expand the V2 Smoothieboard in order to use up to 6 axis.  It gives the breakouts for step/dir/en along with endstops for the axes and connections which are not on the mainboard.
It uses 4 of the Gadgeteer headers to add these functions:

-Step/Dir/En for all 6 axes (bidirectional level shifted)

-Endstop min/max for ABC axes (buffered and identical to the XYZ Endstops on the mainboard)

-4 small FETs (2n7002) which are connected to HWPWM so they can be used for things like hobby servos, BLtouch, small devices, etc. 

-UART0 breakout (bidirectional level shifted)

-EStop input (bidirectional level shifted)

-Vfet in for supplying a voltage other than 5v to run things like hobby servos.  (Jumper selected and disabled by default. 5v default voltage to header)

-Header to breakout all functions to a daughterboard or large single harness.  (i.e. Parallel port connector board for retrofitting existing machines)

PDF Schematic https://github.com/Ccecil/6-Axis-Breakout/blob/main/6AxisBreakout/6AxisBreakout.pdf

<img width="1723" height="960" alt="6AxisBreakoutTop" src="https://github.com/user-attachments/assets/6e85c686-0af0-4fd4-987c-c7e973a597da" />
<img width="1723" height="960" alt="6AxisBreakoutBot" src="https://github.com/user-attachments/assets/7506d606-774e-4141-a341-f6359a646ccc" />

