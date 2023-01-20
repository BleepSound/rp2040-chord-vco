---
permalink: /index.html
layout: single
---

# RP2040 VCO (Clone, made by Hagiwo)

VCO clone, originally made by HAGIWO ([link](https://note.com/solder_state/n/n64b91a171218) in japanese)

RP2040 chord VCO clone in SMD.

5-polyphonic Chord VCO module.
There are 8 types of tones.
With a built-in quantizer and automatic harmonics function, if you input a suitable CV, it will play a nice chord progression.

## Schematics

![schematic](documentation/image/RP2040-VCO-schematic.svg)


## BoM

[See bom globale](documentation/bom/RP2040-VCO-ibom-global.html)

[See bom board jack](documentation/bom/RP2040-VCO-ibom-jack.html)

[See bom board circuit](documentation/bom/RP2040-VCO-ibom-circuit.html)

## build Informations

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Electrolytic capacitors

For the next part, always place them without soldering them on: 
- jacks, pots and switches that go throught the front panel

Once placed, put in place the front panel, then fasten all components to it. Once this is done, you can solder them. 

[Build guide]()

## Images

![3D (front)](documentation/image/RP2040-VCO-3D_top.png)

![3D (back)](documentation/image/RP2040-VCO-3D_bottom.png)

![3D (iso)](documentation/image/RP2040-VCO-3D_top30deg.png)


