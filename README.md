# GAL
This is a 4 phase stepper motor driver built with an Generic Array Logic (GAL). I wasn't able to find any information on how to use these obsolete systems, so I wrote all the steps to code it. The full project is in the wiki: https://github.com/Jorghe/GAL/wiki/Stepper-Motor-Driver-with-a-GAL-22V10

For this project, I used several components in order to build this driver.

A 5VDC unipolar 4 phases Stepper motor
Datasheet: http://robocraft.ru/files/datasheet/28BYJ-48.pdf

A GAL 22V10D DIP 
Datasheet: http://www.latticesemi.com/~/media/LatticeSemi/Documents/DataSheets/GAL/GAL22V10DataSheet.PDF

A transistor array to provide the needed voltage a ULN2804
Datasheet: http://pdf1.alldatasheet.com/datasheet-pdf/view/12687/ONSEMI/ULN2803/+02588UllREMIcXOyY.Nw+/datasheet.pdf

Since the transistor array inverts the signals, a NOT gate 7404 is needed to revert that.
Datasheet: http://www4.ujaen.es/~gnofuen/Hoja%20caracteristicas%207404.pdf
