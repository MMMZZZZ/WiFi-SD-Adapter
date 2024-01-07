# WiFi SD Adapter

## Description

microSD to SD adapter with an ESP32-C3 "inbetween". It allows wireless access to the microSD card without removing the SD card from its slot. It does this with two bidirectional bus switches that disconnect the microSD card from the host and connect it to the ESP32 for the duration of the wireless access. 

Includes a single-sided USB C connector for programming. Might only work on a USB A host port though because it's single-sided. The single-sided is necessary to not become too thick for a USB C connector. 

Gerbers, [iBOM](https://htmlpreview.github.io/?https://github.com/MMMZZZZ/WiFi-SD-Adapter/blob/main/Exported/WiFi-SD-Adapter-iBom.html), etc. can be found in the [Exported](/Exported) folder. 

## Pics

| ![3D Rendering Top](/Exported/3D%20Rendering%20Top.png) | ![3D Rendering Bottom](/Exported/3D%20Rendering%20Bottom.png) |
|--|--|

| ![PCB Layout Top](/Exported/PCB%20Layout%20Top.png) | ![Schematic](/Exported/Schematic.png) |
|--|--|

## License

This project uses third-party libraries for parts and footprints (all located in the [Mouser-Parts](/Mouser-Parts) folder) to which the following licensing information may not apply. 

Copyright Max Zuidberg 2023.

This source describes Open Hardware and is licensed under the CERN-OHL-W v2 or later.

You may redistribute and modify this documentation and make products using it under the terms of the CERN-OHL-W v2 (https:/cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-W v2 for applicable conditions. 

Source location: https://github.com/MMMZZZZ/WiFi-SD-Adapter

As per CERN-OHL-W v2 section 4.1, should You produce hardware based on these sources, You must maintain the Source Location visible on the external case of the WiFi SD Adapter or other product you make using this documentation.
