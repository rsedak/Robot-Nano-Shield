Introduction
============

Robot Nano Shield is Arduino Nano based shield for robots with dimentions compatibile with Lego(TM) liftarms.
For voltage stability L78S05CV Positive-Voltage regulator is used, and for power supply you can use two Li-Ion 18650 batteries.
During programming please keep in mind next design rules:
- D0-D1 — reserved for Bluetooth module (TX have onboard resistor voltage devider for HC-06 module)
- D2-D7 — reserved for H-bridge module (aka. L298N Dual H Bridge)
- D8 — reserved for servo motor
- D9-11 — reserved for RGB LED with onboard resistors
- D12-D13 — reserved for ultrasonic sensor HC-SR04
- A4-A5 — reserved for I2C communication with onboard pull-up resistors


Notice
------
Bluetooth module has to be disconnected during uploading a program to the Arduino Nano. 


Contributors
------------
- Petar Jurković had an idea for the shield with dimensions and features.
- Ines Sedak drew PCB back side picture.
- Robert Sedak did all design.

Application
-----------
Petar Jurković made video with Robot Nano Shield applicatino in his robot:
[![Shield application](http://img.youtube.com/vi/B9CNlWZxvcw/0.jpg)](http://www.youtube.com/watch?v=B9CNlWZxvcw "Shield application")

![Robot Nano Shield Application](https://flic.kr/p/2gizjZQ) 

Bill Of Materials
-----------------
  
- 1 ea., PCB from [PCBway.com](https://www.pcbway.com/project/shareproject/Robot_Nano_Shield.html)
- 2 ea., 560 ohm 1/4W 1% Resistor (R2, R3)
- 2 ea., 1K ohm 1/4W 1% Resistor (R1, R4)
- 1 ea., 2K ohm 1/4W 1% Resistor (R5)
- 2 ea., 10K ohm 1/4W 1% Resistor (R6, R7)
- 1 ea., RGB LED 5mm common Katode (D1)
- 1 ea., 1N5400 Rectifier Diode (D2)
- 1 ea., L78S05CV Positive-Voltage regulator (U1)
- 1 ea., 10uF/25V Radial Aluminium Electrolytic Capacitor (C1)
- 1 ea., 220uF/10V Radial Aluminium Electrolytic Capacitor (C2)
- 1 ea., 2 Pin Plug-In Screw Terminal Block Connector 5.08mm Pitch
- 1 ea., 1x40Pin 2.54mm Straight Pin Header - Yellow
- 1 ea., 1x40Pin 2.54mm Straight Pin Header - Red
- 1 ea., 1x40Pin 2.54mm Straight Pin Header - Black
- 1 ea., 1x4 pin 2.54mm Socket Connector
- 2 ea., 1x15 pin 2.54mm Socket Connector
- 1 ea., Aluminum Heatsink Heat Sink with Screw Sets TO-220 Transistor 20×15×10mm


Design Files
------------
This project is designed using Open Source [KiCad](http://kicad-pcb.org/). Design files are located in the [design_files](design_files/) folder.  You can see the [schematic](images/robot_nano_shield_sch.png).

Firmware
--------
This project can be programed using the Open Source [Arduino](https://www.arduino.cc/).


Assembly Instructions
---------------------
TBD


License
-------
[Attribution-ShareAlike 3.0 United States (CC BY-SA 3.0 US)](https://creativecommons.org/licenses/by-sa/3.0/us/)

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

This license is acceptable for Free Cultural Works.
- The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Reference Designs ARE PROVIDED "AS IS" AND "WITH ALL FAULTS". Authors DISCLAIMS ALL OTHER WARRANTIES, EXPRESS OR IMPLIED,
REGARDING PRODUCTS, INCLUDING BUT NOT LIMITED TO, ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE 
Authors may make changes to specifications and product descriptions at any time, without notice. The Customer must notrely on the absence or characteristics of any features or instructions marked "reserved" or "undefined." 
Authors reservesthese for future definition and shall have no responsibility whatsoever for conflicts or incompatibilities arising from future changes to them. The product information on the Web Site or Materials is subject to change without notice. Do not finalize a design with this info.

