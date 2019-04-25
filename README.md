# ev3-g-kitlib
General purpose My Blocks library to simplify programming in Lego's Mindstorms EV3-G (a version of Labview)

MyPrint
===================================================================
MyBlock to simplify printing of debug values to EV3 LCD display screen

Features
(1) Fixed fontsize 2 is used
(2) Input row number is automatically scaled for fontsize 2, no need to skip alternate rows
(3) Screen is not cleared to prevent screen flicker
(4) Trailing blanks are printed to erase any old text on the screen
(5) No need to specify column number

Inputs
(1) Row: Number of row to print at, 0 to 5 
(2) Name: Name of variable to print, example "Light"
(3) Value: Numeric value to print, example is output from Color Sensor

Example
(1) Input: 0, Light, output from Color Sensor (reflected light measurement)
(2) Output: Light=87
