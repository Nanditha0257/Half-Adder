# Half Adder PCB Design using KiCad

## 📌 Overview
This project implements a **Half Adder** using TTL logic ICs and demonstrates the complete PCB design workflow in **KiCad**. The design includes schematic capture, PCB layout, routing, and 3D visualization.

## 🛠️ Software Used
- KiCad 9
- PCB Editor
- Schematic Editor
- 3D Viewer

## 🔩 Components Used
- 74LS86 (XOR Gate)
- 74LS08 (AND Gate)
- 2 × 2-Pin Connectors
- +5V Power Supply
- GND

## ⚙️ Working Principle
A Half Adder performs the addition of two single-bit binary inputs.

- **Sum (S) = A ⊕ B**
- **Carry (C) = A · B**

## 📊 Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |

## 📂 Project Structure

```
Half-Adder-KiCad/
│── Schematic/
│   └── halfadder.kicad_sch
│
│── PCB/
│   └── halfadder.kicad_pcb
│
│── Images/
│   ├── Schematic.png
│   ├── PCB_Layout.png
│   └── 3D_View.png
│
└── README.md
```

## 📷 Project Preview

### Schematic
(Add your schematic screenshot here)

### PCB Layout
(Add your PCB layout screenshot here)

### 3D View
(Add your 3D render here)

## ✨ Features
- Complete schematic design in KiCad
- Single-layer PCB routing
- 3D PCB visualization
- Beginner-friendly digital electronics project
- Uses standard 74LS TTL logic ICs

## 🚀 Future Improvements
- Full Adder PCB
- 4-bit Ripple Carry Adder
- LED output indicators
- Input switches
- Simulation using ngspice

## 👩‍💻 Author

Nanditha

Electronics and Communication Engineering (ECE)

Learning PCB Design • Embedded Systems • VLSI • IoT
