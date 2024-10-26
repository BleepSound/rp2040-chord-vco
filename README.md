# RP2040 VCO (Clone, made by Hagiwo)

VCO clone, originally made by HAGIWO ([link](https://note.com/solder_state/n/n64b91a171218) in japanese)

RP2040 chord VCO clone in SMD.

5-polyphonic Chord VCO module.
There are 8 types of tones.
With a built-in quantizer and automatic harmonics function, if you input a suitable CV, it will play a nice chord progression.

**Switch indications:**

You'll notice numbers along the central 3 position switch. The table below explains each position's function. 

| Position |     1    |        2        |          3         |
|----------|:--------:|:---------------:|:------------------:|
| Function | arpeggio | chord with root | chord without root |


## Schematics

![RP2040 VCO schematic](documentation/image/RP2040-VCO--Schematic.svg)

## BoM

[See bom](documentation/bom/RP2040-VCO_V1.2--iBoM.html)

## Build Informations

Full CMS build

:warning: When building this module, do it in this order (from smallest component to highest):

- Start by soldering all the CMS components in the order you want on both sides of the PCB.
- Then do all the through hole components
- To solder the headers, place them and place both PCBs in their final postion before fully soldering the pin headers/sockets.

For the next parts, always place them without soldering them on: 
- jacks, pots and switches that go throught the front panel

Once placed, put the front panel in place, then fasten all components to it. Once this is done, you can solder all the remaining components.

### V1.1
- you HAVE TO rotate SW1 180° for the built in LED to work.
- Issues on front panel (wrong label and missing info)

### V1.2
 - Fix issues on SW1
 - Update front panel look to include all informations

## Images

![3D (front)](documentation/image/RP2040-VCO-3D_top.png)

![3D (back)](documentation/image/RP2040-VCO-3D_bottom.png)

![3D (iso)](documentation/image/RP2040-VCO-3D_top30deg.png)

## Software

You'll find the software for that module in the soft folder.

The microcontroler model is: **Seeed XIAO RP2040**

To flash it, use a usb-c cable to connect the RP2040 to your computer and use the arduino IDE (or your preferred IDE) to flash the microcontroler.

If you need any help, you can find a tutorial on how to flash a software via arduino onto a RP2040 [here](https://wiki.seeedstudio.com/XIAO-RP2040-with-Arduino/).