# PTC Heater Mount and Duct
<img width="1154" height="921" alt="image" src="https://github.com/user-attachments/assets/5ad5f4c5-45f4-4953-bee2-cf2de7a145e6" />
<img width="931" height="955" alt="image" src="https://github.com/user-attachments/assets/89f2c3b8-61e8-466b-8d74-0ab8577252d7" />
<img width="1192" height="974" alt="image" src="https://github.com/user-attachments/assets/7af717a2-d5cf-4ec8-a350-9a6a1f875673" />
<img width="1229" height="1008" alt="image" src="https://github.com/user-attachments/assets/3daf61a2-3915-47b6-b836-77c8bf0736b8" />
## Installation Instructions

### ⚠️ Safety Notice
This mount is intended for use with PTC heaters inside enclosed 3D printers.
Ensure all wiring is properly insulated and strain-relieved. (Ensure a thermal cutoff fuse is implemented directly touching the heater)
Never power the heater without proper thermal control and safety protection.

---

### Required Hardware

-BOM (https://github.com/Fishyfabspnw/ptc-heater-mount-and-duct/blob/main/BOM.md#bill-of-materials)
- High-temp wire (silicone insulated recommended/ or FEP wire)
- Thermal fuse (REQUIRED!!!)
- SSR( Solid State Relay)

---

### Print Recommendations For Wire Shroud (High Temp FILAMENTS ONLY!!!)

Material: ASA-GF / PPS-CF / NYLON 
Do NOT use PLA inside heated chambers.  
Walls: 4+  
Infill: 45%+  
First Layer Height: 0.25mm
Layer Height: 0.2mm    
Seam: Back

---

### Assembly Steps

1. Prep SLM/Laser Cut part by tapping. <img width="1039" height="917" alt="image" src="https://github.com/user-attachments/assets/2e84aacb-9814-4255-a9f9-e11380a2e627" />

2. Implement a 121c thermal cutoff fuse to the power loop. (i used a rivot)
3. Safely drill a hole through the fins in the PTC-Heater to allow for a thermistor to be placed into the fins. 
4. Apply Boron Nitrade paste into the hole before embedding the thermistor. 
5. Mount standoff's on the orginal PTC Heater shroud with the M4x8mm SHCS.
6. Mount the SLM printed duct to the other side of the standoff with the M4x8mm SHCS.
7. Mount fan and laser cut Part. (The laser cut part is meant to be sandwiched between the fan and the SLM printed duct)
8. Mount wire shroud over the front with the M3x45mm SHCS.
9. Mount the assembly to the extrusion with the M5x8mm SHCS.

---

### Recommended Operating Limits

- Max chamber temperature: [89c]
- Heater wattage tested: [250W]
- Max Heater Temp [121c]

---

### Notes

- Designed for enclosed CoreXY-style printers.
- Ensure adequate airflow across heater fins.
- Add a thermal fuse in series for additional safety.

## Contents

* `Cad` – STEP CAD exports.
*  `SLM` – SLM Parts.
* `BOM.md` – bill of materials with suppliers/part numbers.

## Heater

This mount and duct is designed for the [PTC Heater](https://www.amazon.com/dp/B07NYX5DKD).

## License

This project is licensed under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. See the `LICENSE` file for details.
