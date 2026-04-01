# USB-to-TTL Serial UART Converter (Experimental Layout)

This repository contains the KiCad design files for a USB-to-TTL converter based on the **CH340G** IC and a **USB-C** connector. 

## ⚠️ Project Status: On Hold / Experimental
This project is an architectural study rather than a finished, production-ready PCB. Development has been paused at the routing stage for the following technical reasons:

- **Routing Constraints:** The 16-pin USB-C connector features an extremely tight pin pitch. Standard design rules (clearance) in KiCad caused routing conflicts in the breakout area.
- **Design Study:** The project successfully demonstrates schematic capture, footprint assignment, component placement optimization, and ground plane (copper pour) application.


## 🖼️ Project Visuals

### 1. Schematic Design
The electrical connections and component logic are defined in the schematic below:

![Schematic View](USB-to-TTL_sch.png)

### 2. 3D Render
The physical layout and component placement on the PCB:

![3D Render](USB-to-TTL_3d.png)

### 3. PCB Layout (Work in Progress)
The current state of the copper layers and ground plane:

![PCB Layout](USB-to-TTL_pcb.png)

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
