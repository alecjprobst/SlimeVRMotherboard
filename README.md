# SlimeVR Motherboard

This is a project to make it easier to create SlimeVR trackers. This project reduces the amount of cable management needed when making SlimeVR trackers by providing a PCB that can be made for only $2. Beginner instructions on how to buy a PCB are below

# Sections

 - Parts and Setup
 - PCB Files and Submission
 - STL Files and Description
 - Assembly Instructions

## Parts and Setup

These PCB's use the official SlimeVR [Components](https://docs.slimevr.dev/components-guide.html) and [Tracker Schematics](https://docs.slimevr.dev/tracker-schematics.html). The PCB is compatible with either the BNO08X or MPU6050 IMU's and has locations for optional Battery Sense resistors and Charge Diodes. With this PCB, you will only need wire for connecting the IMU's. 

All of the parts below are linked in the SlimeVR [Components](https://docs.slimevr.dev/components-guide.html) guide.
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

## STL Files and Description

All STL's were created in Fusion360. Please feel free to modify them as you see fit. If you do not have a 3D printer, you can print the cases from jcpcb or you may want to consider 3D printing sites like [Hubs](https://www.hubs.com/3d-printing/) or [Sculpteo](https://www.sculpteo.com/en/).

Cases can be printed on an FDM printer at .2mm layer height.

A single SlimeVR Tracker case requires two parts, a Higher_Body.stl and a Lower_Body.stl. Both of these parts can be printed without supports. The Lower_Body.stl has poles to mount the PCB inside of the case so it does not shake. It is recommended to add hot glue to make sure the PCB does not move at all. Both cases have holes for charging and access to the D1 Mini as well as the switch and AUX tracker cable. The cases should slide together after being printed and should be somewhat difficult to pull apart.

## Assembly Instructions
A Knolled layout of all parts needed for one tracker is shown in this picture. Please note that your IMU's may look different and the resistor and diodes are optional.
![Part Knolling](https://github.com/alecjprobst/SlimeVRMotherboard/blob/main/Images/Part%20Knolling.jpg)
![Part Knolling](Images/Part%20Knolling.jpg)
