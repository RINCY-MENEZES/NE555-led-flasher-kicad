# NE555 LED Flasher PCB

A compact PCB design of an **NE555 Timer LED Flasher** developed using **KiCad 9**. This project demonstrates the complete PCB design workflow, including schematic capture, PCB layout, routing, design rule verification (DRC), Gerber file generation, and 3D visualization.

---

## Project Overview

This project implements an LED flasher circuit using the **NE555 Timer IC** configured in **Astable Mode**. The timer continuously generates a square wave, causing the LEDs to blink at a fixed frequency determined by the resistor-capacitor (RC) network.

The project was designed to strengthen practical skills in PCB design and electronics hardware development.

---

## Features

- PCB designed using KiCad 9
- NE555 Timer configured in Astable Mode
- Compact single-layer PCB layout
- Complete schematic capture
- PCB routing and component placement
- 3D PCB visualization
- Design Rule Check (DRC) passed with **0 Errors** and **0 Warnings**
- Gerber files generated for PCB manufacturing

---

## Components Used

- NE555 Timer IC
- Resistors
- Capacitors
- LEDs
- 2-Pin Power Connector

---

## Software Used

- KiCad 9

---

## Project Snapshots

### Schematic

---

### PCB Layout

---

### 3D View (Top)

---

### 3D View (Bottom)

---

## Repository Structure

```
NE555-led-flasher-kicad/
│
├── Gerber_Files/
├── Images/
│   ├── Schematic.png
│   ├── PCB_Layout.png
│   ├── 3D_Top.png
│   └── 3D_Bottom.png
│
├── NE555_LED_Flasher.kicad_pcb
├── NE555_LED_Flasher.kicad_pro
├── NE555_LED_Flasher.kicad_sch
├── NE555_LED_Flasher.kicad_prl
├── .gitignore
├── LICENSE
└── README.md
```

---

## Gerber Files

The repository includes Gerber files required for PCB fabrication. These files can be directly used by PCB manufacturers for board production.

---

## Future Improvements

- Optimize PCB size
- Add mounting holes
- Convert the design to an SMD version
- Add a power indicator LED
- Improve silkscreen labeling

---

## Author

**Rincy Menezes**

