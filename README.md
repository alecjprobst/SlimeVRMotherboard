# SlimeVR Motherboard

This is a project to make it easier to create SlimeVR trackers. This project reduces the amount of cable management needed when making SlimeVR trackers by providing a PCB that can be made for only $2. Beginner instructions on how to buy a PCB are below

# Sections

 - Parts and Setup
 - PCB Files and Submission
 - STL Files and Description
 - Assembly Instructions

## Parts and Setup

These PCB's use the official SlimeVR [Components](https://docs.slimevr.dev/diy/components-guide.html) and [Tracker Schematics](https://docs.slimevr.dev/diy/tracker-schematics.html). The PCB is compatible with either the BNO08X or MPU6050 IMU's and has locations for optional Battery Sense resistors and Charge Diodes. With this PCB, you will only need wire for connecting the IMU's. 

All of the parts below are linked in the SlimeVR [Components](https://docs.slimevr.dev/diy/components-guide.html) guide.
This PCB is made for use with the following parts:

 - D1 Mini
 - TP4056 Charging Board (any connector)
 - 3.7V Batteries
 - SS22F32 DPDT Switch
 - Either BNO08X or MPU6050 IMU's
 - (Optional) 180k ohm Battery Sense Resistor
 - (Optional) 1N5817 Charge Diodes

3D printable cases for the SlimeVR Trackers are included in this repo. They require no supports and no hardware to put together. See the STL Files and Description below

## PCB Files

All PCB files are included in this repo in the KiCAD Schematic Folder. Please feel free to modify them as you see fit. KiCAD was use to create this project which is a free and opensource tool to create PCB's. 

## PCB Submission 

Buying a PCB is very simple. Download this repo by clicking the green "Code" button towards the top of this page then click "Download ZIP". You will start downloading a ZIP file contain this entire repo. Open the zip file and find the "SlimeVR Motherboard Gerbers V1.1.zip" and "JLCPCB_Upload_Settings.png" file. Drag these to your desktop or a folder of your choice. 

To buy the PCB, we will use JLC PCB. Their website can be found here: https://jlcpcb.com/. Click on the text that says "Add gerber file" and find and select the "SlimeVR Motherboard Gerbers V1.1.zip" you just moved. Open the "JLCPCB_Upload_Settings.png" file and make sure the settings between the picture and what jlcpcb have shown you are the same. Feel free to change the PCB color to whatever you like (purple looks great!). Click "Save to Cart" then buy your PCB's. This process should be the same as any other online purchase from here on out.

![Images/JPCPCB_Upload 1.png](Images/JLCPCB_Upload%201.png)

![Images/JLCPCB_Upload Settings.png](Images/JPCPCB_Upload%20Settings.png)

## STL Files and Description

All STL's were created in Fusion360. Please feel free to modify them as you see fit. If you do not have a 3D printer, you can print the cases from jcpcb or you may want to consider 3D printing sites like [Hubs](https://www.hubs.com/3d-printing/) or [Sculpteo](https://www.sculpteo.com/en/).

Cases can be printed on an FDM printer at .2mm layer height.

A single SlimeVR Tracker case requires two parts, a Higher_Body.stl and a Lower_Body.stl. Both of these parts can be printed without supports. The Lower_Body.stl has poles to mount the PCB inside of the case so it does not shake. It is recommended to add hot glue to make sure the PCB does not move at all. Both cases have holes for charging and access to the D1 Mini as well as the switch and AUX tracker cable. The cases should slide together after being printed and should be somewhat difficult to pull apart.

## Assembly Instructions
A Knolled layout of all parts needed for one tracker is shown in this picture. Please note that your IMU's may look different and the resistor and diodes are optional.

![Images/Part Knolling.jpg](Images/Part%20Knolling.jpg)

To place the resistors, first bend them as shown below

![Image/Resistor and Diode Bends.jpg](Images/Resistor%20and%20Diode%20Bends.jpg)

Place these resistor and diodes as such

![Images/Diode and Resistor Placement.jpg](Images/Diode%20and%20Resistor%20Placement.jpg)

Solder the resistor and diodes as shown in the images below. Cut the excess wire when finished soldering.

![Images/Diode_Resistor Soldering 1.jpg](Images/Diode_Resistor%20Soldering%201.jpg)

![Images/Diode_Resistor Soldering 2.jpg](Images/Diode_Resistor%20Soldering%202.jpg)

![Images/Diode_Resistor Soldering 3.jpg](Images/Diode_Resistor%20Soldering%203.jpg)

![Images/Diode_Resistor Soldering 4.jpg](Images/Diode_Resistor%20Soldering%204.jpg)

To solder the TP4096, take 6 pins and place them as such

![enter image description here](Images/TP4096%20Solder%201.jpg)

Solder them on both the top of the TP4096 and the bottom of the PCB as shown below. Cut the excess pins on the top and bottom when finished soldering.

![Images/TP4096 Solder 2.jpg](Images/TP4096%20Solder%202.jpg)

![Images/TP4096 Solder 3.jpg](Images/TP4096%20Solder%203.jpg)

To solder the D1 Mini, place two 1x8 pins in the holes as shown below.

![Images/D1 Mini Soldering 1.jpg](Images/D1%20Mini%20Soldering%201.jpg)

Solder the top of the D1 Mini and bottom of the PCB as shown below. Cut the excess pins on the top and bottom when finished soldering.

![Images/D1 Mini Soldering 2.jpg](Images/D1%20Mini%20Soldering%202.jpg)

![Images/D1 Mini Soldering 3.jpg](Images/D1%20Mini%20Soldering%203.jpg)

![Images/D1 Mini Soldering 4.jpg](Images/D1%20Mini%20Soldering%204.jpg)

Before soldering the switch, cut the excess hole mount as shown in the before and after pictures below.

![Images/Switch Cut 1.jpg](Images/Switch%20Cut%201.jpg)

![Images/Switch Cut 2.jpg](Images/Switch%20Cut%202.jpg)

To keep the Switch in place, it is recommended to use tape as shown below. Once secured, solder the switch from the bottom of the PCB. Cut the excess switch contacts after soldering

![Images/Switch Solder 1.jpg](Images/Switch%20Solder%201.jpg)

![Images/Switch Solder 2.jpg](Images/Switch%20Solder%202.jpg)

To add the IMU, first cut out 6 wires of around 25mm long and strip the ends of the wires as shown below.

![Images/IMU Wiring.jpg](Images/IMU%20Wiring.jpg)

Solder the wires as shown below. Generally it is easier to solder to the PCB first then the IMU but this may be personal preference. Cut the excess wire after soldering. Note: the AD0 wire is missing in the two pictures below and is required.

![Images/IMU Soldering 1.jpg](Images/IMU%20Soldering%201.jpg)

![Images/IMU Soldering 2.jpg](Images/IMU%20Soldering%202.jpg)

To Solder the AUX IMU, cut out 6 wires of either 150mm or 300mm in length. The 150mm is used for the ankle/foot IMU's while the 300mm is used for the chest/wait IMU's.

![Images/AUX IMU Wiring.jpg](Images/AUX%20IMU%20Wiring.jpg)

Solder the AUX IMU as shown below. Cut the excess wires after soldering.

![Images/AUX IMU Soldering 1.jpg](Images/AUX%20IMU%20Soldering%201.jpg)

![Images/AUX IMU Soldering 2.jpg](Images/AUX%20IMU%20Soldering%202.jpg)

To solder the battery, solder the ground (black) wire first then the power (red) wire second from the bottom of the PCB. Make sure these wires do not touch as it may cause sparks. Cut the excess wire when finished soldering.

![Images/Battery Soldering.jpg](Images/Battery%20Soldering.jpg)

It is recommended but not required to hot glue all parts as to prevent parts from moving inside the case. Hot gluing the wires will help protect from from strain as well. To assemble the case, put the battery in the Lower Body first.

![Images/Case Assembly 1.jpg](Images/Case%20Assembly%201.jpg)

Next, put the PCB on top of the battery with the ports facing the holes. The holes in the PCB should keep the PCB in place. Make sure that there are no excess wires or pins poking into the battery.

![Images/Case Assembly 2.jpg](Images/Case%20Assembly%202.jpg)

Hot glue the IMU to the Higher Body Case. Make sure the Higher Body Case is lined up correctly so the holes are facing the correct direction. 

![Images/Case Assembly 3.jpg](Images/Case%20Assembly%203.jpg)

Slide the Higher Body Case onto the Lower Body Case to close the SlimeVR Tracker. Make sure no wires get pinched or disconnected and the switch is able to be turned off and on. This completes the hardware assembly of the SlimeVR trackers. To setup the software, continue from the [SlimeVR Tracker Firmware Guide](https://docs.slimevr.dev/firmware/updating-firmware.html)

![Images/Case Assembly 4.jpg](Images/Case%20Assembly%204.jpg)

![Images/Case Assembly 5.jpg](Images/Case%20Assembly%205.jpg)


