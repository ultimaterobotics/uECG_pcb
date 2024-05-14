## uECG PCB version 4.52
 Changelog:

- Replaced AD8606 op amp with a pair of TLV271s;
- LDOs (3.3V for digital, 3V for analog side) were mixed in the previous version; strangely this didn’t affect functioning, but now this is fixed;
- Replaced BMI160 with LSM6DS3TR-C;
- Changed C6 capacitor from 2.2uF to 10uF for better low frequency performance;
- Replaced circuit protection (red LED) with diodes for more reliability;
- Changed charge resistor to 8.2K Ohm to fit the battery charging better;
- Replaced MCP71831 charger IC with TP4054; 
- Added thermistor for measuring temperature;
- Changed RGB LED to different part number;
- Added Ultimate Robotics logo on the back of the PCB.


## uECG device PCB version 4.5

PCB design in KiCAD. The main difference vs previous versions is that power is controlled via button, and slider switch is used only for long storage / shipping (and also to reset the firmware if something went really wrong).

Main project repository: https://github.com/ultimaterobotics/uECG
