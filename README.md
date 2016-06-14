##BLE CUBE - PCB Design
This is the repository for all PCB Design files. Included in this repository is:

####BLE Card
This card features three 8-bit shift registers. The parallell outputs of these can be found alongside the edges of the card.
BLE Card supports two types of accelerometers. One internal [(LIS2DH12)](http://www.st.com/content/ccc/resource/technical/document/datasheet/12/c0/5c/36/b9/58/46/f2/DM00091513.pdf/files/DM00091513.pdf/jcr:content/translations/en.DM00091513.pdf) that features its own traces and a header pin for an external accelerometer.

For more information, see pin assignements and pin map.

Also available is Components and Bill of Materials, BOM. Some of the used components are not included. See bottom of the BOM for details.
Further information on the circuits reference design can be found at Nordic Semiconductors infocenter

**Disclaimer!** This PCB as it is now is designed for use with LEDs that runs on 3V. Resistors are 390 ohm, but should be lower if 3v LEDs are to utilized. This part of the project was significantly modified in our case. This must be kept in mind if you want to replicate the project. In our case, the shiftregisters was modified to run on 4.2V in order to function with the LEDs.

![BLE Card](https://raw.githubusercontent.com/blecube/PCB-Design/master/images/PCB%20Design%20-%20BLE%20Card%20-%203D%20-%20small.png)


####Adapter Card
* Designed for using [Adafruits chargecircuit](https://www.adafruit.com/product/259).
* Can be modified to send battery status lines to either P0.30 and P0.29, or P0.13 and P0.14. These can be used to program the cube to indicate "charging" or "charge complete".


![BLE Card](https://raw.githubusercontent.com/blecube/PCB-Design/master/images/PCB%20Design%20-%20Adapter%20Card%20-%20Small.png)


####Schematic
The file called Schematics - BLE Card shows all connections, nets and components on the BLE Card.


####Recommended battery
If the adafruit charger is used, we recommend this battery to be used alongside our adapter card: [https://www.adafruit.com/products/328](https://www.adafruit.com/products/328)




> Created by Rasmus Espset