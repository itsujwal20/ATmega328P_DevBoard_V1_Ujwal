# ATmega328P Dev Board V1 - by Ujwal

This is a custom 2-layer development board designed using KiCad around the ATmega328P microcontroller. It includes essential features for easy prototyping, programming, and embedded development.

---

## 📸 Project Preview

### Circuit Diagram
![Circuit Diagram](images/CircuitDiagram.png)

### PCB Layout  
![PCB Layout](images/Pcb_Layout.png)

### 3D View  
![3D View](images/3D_View_Front.png)
![3D View](images/3D_View_Back.png)

---

## 🔧 Features

- ✅ ATmega328P Microcontroller (DIP-28)
- ✅ Onboard Power Supply (Barrel Jack Input)
- ✅ 16 MHz Crystal Oscillator with 22pF Capacitors
- ✅ Power LED and RESET Circuit
- ✅ FTDI 6-pin Header for Serial Programming
- ✅ All GPIO Pins Broken Out
- ✅ Decoupling Capacitors (100nF) on VCC/AVCC
- ✅ Ground Plane for Noise Reduction
- ✅ 2-layer PCB Design

---

## 📁 Folder Structure
```
ATmega328P_DevBoard_V1_Ujwal/
├── ATmegafile/
│ ├── schematics/
│ ├── pcb_layout/
│ ├── gerbers/
│ └── ...
├── images/
│ ├── pcb_layout.png
│ └── 3d_view.png
├── README.md
└── LICENSE
```
---

## 🔌 Serial Programming Header (FTDI)

| FTDI Pin | Connects To | Notes                     |
|----------|-------------|---------------------------|
| GND      | GND         | ✔                         |
| VCC      | +5V         | ✔                         |
| TXD      | PD0 (RX)    | MCU RX                    |
| RXD      | PD1 (TX)    | MCU TX                    |
| DTR      | RESET via 100nF | Enables auto-reset   |
| RTS      | (Optional)  | Usually not connected     |

---

## 🛠️ How to Build

1. **Clone this Repo**  
   ```bash
   git clone https://github.com/itsujwal20/ATmega328P_DevBoard_V1_Ujwal.git

2. **Open in KiCad**
   Open the .kicad_pro file from the ATmegafile folder.

3. **Generate Gerbers (Already Included)**
    Use KiCad → File → Plot → Select Layers → Generate Drill Files → ZIP for fabrication.



**🔋 Power Supply Options**
- 5V Regulated Supply via Barrel Jack
- Can also be powered via FTDI (USB to Serial)

**🧪 Applications**
- Embedded systems prototyping
- Arduino-compatible custom projects
- Educational/teaching tool
- Robotics and automation boards

**📝 License**
This project is licensed under the MIT License.
Feel free to fork, modify, and use it commercially or personally.

🙌 Developed by
Ujwal Kumar S
``` https://github.com/itsujwal20 ``` 


