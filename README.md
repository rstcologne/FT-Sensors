# FT-Sensors

On this page I share my hopefully growing list of designs to integrate common sensor boards for Arduino (and others) with the FT building block system. 

## Print Settings

The parts shown are printed in ABS at 0,2mm layer height. One goal of the designs is printability without supports. For example, the sunk screw holes are closed with one layer for the thinner channel to print cleanly. Otherwise the thinner channel would start in thin air or would require support)

## FT Box Generic

Parametric template file to start designing custom boxes. Primarily important are the paramaters

* length in blocks (15mm)
* width in blocks (15mm)
* height in blocks (15mm)

which set the box size in FT size units. From there a top and bottom half part is generated which can then be modified to fit particular components. 

## FT Proximity Sensor

Case for common proximity sensors like this:

<img src="https://github.com/rstcologne/FT-Sensors/blob/main/Images/FTPS-Sensor.jpg?raw=true" width=150/>

### BOM
* The proximity sensor board
* 4 M2 8mm self tapping screws (for the case)
* 1 M2 6mm self tapping screw (to mount the sensor)
* 3 wire servo cable

<img src="https://github.com/rstcologne/FT-Sensors/blob/main/Images/FTPS-Prints.jpg?raw=true" width=250/>

### Instructions
* Print parts
* Remove the PIN headers
* pass the servo cable through the slot (it's deliberately tight)
* solder the wires to the board
* mount the board and attach it with the 6mm screw
* adjust cable and close case
* attach both halfs with 4 8mm screws


