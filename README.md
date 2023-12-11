# TVZ ACS712 Current sensing module

[![Version](https://img.shields.io/github/v/release/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/pulls)

 Expansion board for NI myDAQ Student Data Acquisition Device, developed in 2022 for students studying at Zagreb university of applied sciences.
 It enables quick and easy .VI development without the need of connecting different modules via breadboard and jumpers.
 
 ## Features
 - 4mm banana plugs for sensors IP+ and IP- pins
 - 3 different capacitor values for filtering (switchable via jumper pins)
 - powering sensor via miniUSB or male pins
 - power LED
 - Probe clips for easy oscilloscope connections

## Images
<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/jkordek1/myDAQ-Expansion-Board/main/Images/Front.jpg">
</p>

## Project folder structure
    .
    ├── ...
    ├── Images                  # Images of the project
    ├── KiCADFiles              # Main folder
    │   ├── 3d models           # 3d models of components
    │   ├── Datasheet           # Datasheet collection
    │   ├── Graphics            # Custom graphics for PCB
    │   ├── gerber              # gerber output folder
    │   ├── myDAQExpansionBoard # Main folder for KiCAD files
    │   └── Schematic.pdf       # Project schematic
    └── ...

 
