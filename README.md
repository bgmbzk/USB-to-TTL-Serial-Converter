# USB-to-TTL Serial UART Converter (Experimental Layout)

This repository contains the KiCad design files for a USB-to-TTL converter based on the **CH340G** IC and a **USB-C** connector. 

## ⚠️ Project Status: On Hold / Experimental
This project is an architectural study rather than a finished, production-ready PCB. Development has been paused at the routing stage for the following technical reasons:

- **Routing Constraints:** The 16-pin USB-C connector features an extremely tight pin pitch. Standard design rules (clearance) in KiCad caused routing conflicts in the breakout area.
- **Design Study:** The project successfully demonstrates schematic capture, footprint assignment, component placement optimization, and ground plane (copper pour) application.

## 🖼️ Project Visuals
Below is the 3D render of the current component placement:

![3D Render of PCB](USB-to-TTL_3d.png)

*Note: The image above shows the 3D model of the board as designed in KiCad's 3D Viewer.*

## 🛠️ Technical Specifications
- **Main IC:** CH340G (USB-to-Serial)
- **Connector:** USB Type-C (16-pin Surface Mount)
- **Software:** KiCad 8.0
- **Features:** Integrated crystal oscillator circuit, decoupling capacitors, and designated UART breakout pins.

## 📝 Learning Outcomes
This experiment provided hands-on experience with:
1. High-density connector footprints.
2. Managing ground planes in a mixed-signal environment.
3. Troubleshooting Design Rule Check (DRC) violations in tight spaces.
