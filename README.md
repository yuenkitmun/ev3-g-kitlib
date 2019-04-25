# ev3-g-kitlib
General purpose My Blocks library to simplify programming in Lego's Mindstorms EV3-G (a version of Labview)

MyPrint
===================================================================
MyBlock to simplify printing of debug values to EV3 LCD display screen

Features
Fixed fontsize 2 is used
Input row number is automatically scaled for fontsize 2, no need to skip alternate rows
Screen is not cleared to prevent screen flicker
Trailing blanks are printed to erase any old text on the screen
No need to specify column number

Inputs
Row: Number of row to print at, 0 to 5 
Name: Name of variable to print, example "Light"
Value: Numeric value to print, example is output from Color Sensor

Example
Input: 0, Light, output from Color Sensor (reflected light measurement)
Output: Light=87
