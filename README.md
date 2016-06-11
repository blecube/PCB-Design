##BLE CUBE - PCB Design
This is the repository for all PCB Design files. Included in this repository is:

####BLE Card
* This card features three 8-bit shift registers. The parallell outputs of these can be found alongside the edges of the card.
* BLE Card supports two types of accelerometers. [One internal (LIS2DH12)](http://www.st.com/content/ccc/resource/technical/document/datasheet/12/c0/5c/36/b9/58/46/f2/DM00091513.pdf/files/DM00091513.pdf/jcr:content/translations/en.DM00091513.pdf) that features its own traces and a header pin for an external accelerometer.

* For info about IOs on edges, see pin assignements and pin map

*Components and Bill of Materials BOM, some used components are not included
* Reference design - further info at NS infocenter
*Disclaimer! This pcb as it is now is designed for use with leds that should be run with 3V. Resistors are 390 ohm but should be lower if 3v leds ar to utilized. This part of the project was significantly modified in our case.

![BLE Card](https://raw.githubusercontent.com/blecube/PCB-Design/master/images/Utlegg%20-%203d%20%E2%80%93%20small.png)


####Adapter Card
* Designed for using [Adafruits chargecircuit]https://www.adafruit.com/product/259).
* Can be modified to send battery info to either P0.xx and P0.xx, or P0.yy and P0.yy.


![BLE Card](https://raw.githubusercontent.com/blecube/PCB-Design/master/images/Utlegg%20-%203d%20%E2%80%93%20small.png)


####Schematic
The file called schematics - BLE Card shows all connections on the BLE Card.


####Reccomended battery
We reccommend this battery to be used alongside our adapter card.




> Created by Rasmus Espset