# ESP32 4-Layer Development Board

## Overview

This project is a custom 4-layer ESP32 development board designed in KiCad using the official Espressif ESP32-DevKitC V4 reference design as the foundation. The objective was to understand professional PCB design practices, including schematic capture, component placement, signal routing, power distribution, and multilayer PCB stack-up.

## Features

* ESP32-WROOM-32 module
* 4-layer PCB design
* USB-UART programming interface (CP2102)
* AMS1117-3.3 voltage regulator
* EN and BOOT buttons
* USB connector for programming and power
* Standard GPIO pin headers
* Ground and power planes for improved signal integrity

## PCB Stack-up

* **F.Cu** – Signal routing and components
* **In1.Cu** – Solid Ground Plane
* **In2.Cu** – 3.3 V Power Plane
* **B.Cu** – Signal routing and components

## Design Process

1. Created the schematic using KiCad.
2. Verified the design with Electrical Rules Check (ERC).
3. Assigned footprints to all components.
4. Imported the schematic into the PCB Editor.
5. Designed a 4-layer PCB with dedicated ground and power planes.
6. Routed signals while maintaining ESP32 antenna keep-out requirements.
7. Verified the PCB using Design Rules Check (DRC).
8. Generated Gerber and drill files for manufacturing.

## Main Components

* ESP32-WROOM-32
* CP2102 USB-to-UART Bridge
* AMS1117-3.3 Voltage Regulator
* USB Connector
* Push Buttons (EN and BOOT)
* LEDs
* Resistors and Capacitors
* Pin Headers

## Software Used

* KiCad 10
* Git
* GitHub

## Project Files

* Schematic (.kicad_sch)
* PCB Layout (.kicad_pcb)
* Gerber Files
* Drill Files


## References

* Espressif ESP32-DevKitC V4 Reference Design
* KiCad Official Documentation

## Author

**Sreelekshmi H**
First-Year Electronics and Communication Engineering Student
Cochin University of Science and Technology (CUSAT)
