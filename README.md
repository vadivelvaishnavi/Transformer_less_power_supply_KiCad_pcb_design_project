# Transformer-less Power Supply  <br>

<img width="1341" height="356" alt="image" src="https://github.com/user-attachments/assets/cb6249f0-ab54-4137-a752-130765b54de2" />

## Overview
This project demonstrates the design of a **transformer-less power supply** using KiCad. <br>
The circuit converts AC mains input into a regulated DC output using capacitive voltage dropping, rectification, filtering, and regulation. <br>
Developed for pcb design competition held at Shakespeare Gallery in TT. <br>

---

### Key Components
| Component | Value/Part | Notes |
|-----------|------------|-------|
| R1, R2    | 20kΩ       | Voltage divider |
| R3        | 1MΩ        | Bleeder resistor |
| R4        | 2.2kΩ      | LED current limit |
| C1        | 0.1µF      | Filter capacitor |
| C2        | 1000µF     | Bulk capacitor |
| C3        | 470µF      | Output smoothing |
| D1–D4     | 1N4001     | Bridge rectifier |
| D5, D6    | Zener diodes | Voltage regulation |
| D7        | LED        | Power indicator |
| U1        | LM7805     | 5V regulator |
| J1        | AC input terminal |
| J2        | DC output terminal |

---

## Software
- **EDA Tool:** KiCad 9.0.7  
- **Gerber Viewer:** KiCad Gerber Viewer (or any online Gerber viewer)  
- **Version Control:** Git + GitHub  

---

## Visuals

![less](schematic/sch.png)
![less](pcb/pcb.png)
![less](3d_view/3d_view_top.png)

---

## Safety Disclaimer
This project involves **direct connection to mains AC**.  
It is intended for **educational and simulation purposes only**.  
Do not attempt to build or test without proper isolation, supervision, and protective equipment.  
Always follow electrical safety standards.

---
## Team:
V VAISHNAVI <br>
GURUPRIYAA N <br>
DISHIKA G <br>

## Institution: Vellore Institute of Technology (VIT)

Support If you found this project inspiring, consider giving it a star on GitHub to support further development and encourage open-source innovation.





