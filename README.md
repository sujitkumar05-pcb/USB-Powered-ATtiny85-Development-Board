# USB-Powered-ATtiny85-Development-Board

## 1. Project Overview

The USB-Powered ATtiny85 Development Board is a compact and low-cost microcontroller development platform designed for quick prototyping and learning purposes. It is based on the ATtiny85, an 8-bit AVR microcontroller, and can be powered directly through a USB interface, eliminating the need for an external power supply.

This board is intended to simplify development by providing easy access to essential pins, stable power regulation, and support for programming via commonly used USB-based programmers. Its small form factor makes it ideal for embedded applications, wearable electronics, and space-constrained projects.

The project focuses on:

Minimal component count for reliability and ease of assembly

USB power convenience for plug-and-play operation

Compatibility with Arduino-based workflows and AVR toolchains

Educational and hobbyist-friendly design

This development board is suitable for beginners learning microcontroller basics as well as engineers needing a simple ATtiny85-based solution for rapid prototyping.

## 2. Key Learning Objectives

Understand ATtiny85 microcontroller basics

Learn USB-powered circuit design

Practice schematic and PCB layout design

Gain experience in programming and testing AVR microcontrollers
-----

## 3. Tools & Software Used
- **KiCad EDA**
  - Schematic Editor  
  - PCB Layout Editor  
  - 3D Viewer
 
 ---

## 4. Project Files
- Schematic design files (`.kicad_sch`)  
- PCB layout files (`.kicad_pcb`)  
- 3D render images  
- Manufacturing-ready Gerber files  

---

## 5. Block-Level Working Explanation

The USB port supplies 5 V power to the board, which powers the ATtiny85 microcontroller. The microcontroller executes the programmed logic and controls the I/O pins. External components or modules connected to these pins interact with the ATtiny85 for input and output operations.
## 6. Bill of Materials (BOM)
| S. No. | Reference | Value          | Footprint                                             | Qty |
| -----: | --------- | -------------- | ----------------------------------------------------- | --: |
|      1 | C1        | 1 µF           | Capacitor_SMD:C_1210_3225Metric                       |   1 |
|      2 | C2        | 4.7 µF         | Capacitor_SMD:C_1210_3225Metric                       |   1 |
|      3 | C3        | 0.1 µF         | Capacitor_SMD:C_1210_3225Metric                       |   1 |
|      4 | D1        | 1N5819         | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal           |   1 |
|      5 | D2, D3    | BZT52C36       | Diode_SMD:D_SOD-123F                                  |   2 |
|      6 | D4, D5    | LED            | LED_SMD:LED_1210_3225Metric                           |   2 |
|      7 | J1        | Conn_01x03_Pin | Connector:FanPinHeader_1x03_P2.54mm_Vertical          |   1 |
|      8 | J2        | USB Micro      | Connector_USB:USB_A_CNCTech_1001-011-01101_Horizontal |   1 |
|      9 | J3        | Conn_01x06_Pin | Connector_JST:JST_PH_B6B-PH-K_1x06_P2.00mm_Vertical   |   1 |
|     10 | R1        | 1 kΩ           | Resistor_SMD:R_1210_3225Metric                        |   1 |
|     11 | R2, R3    | 66.5 Ω         | Resistor_SMD:R_1218_3246Metric                        |   2 |
|     12 | R4, R5    | 1 kΩ           | Resistor_SMD:R_1218_3246Metric                        |   2 |
|     13 | U1        | L78L05         | Package_SO:SOIC-8_3.9×4.9 mm_P1.27 mm                 |   1 |
|     14 | U2        | ATtiny85-20S   | Package_SO:SOIC-8_5.3×5.3 mm_P1.27 mm                 |   1 |


## 7. Images & Renders

- **Schematic**
<img width="910" height="642" alt="image" src="https://github.com/user-attachments/assets/e7d06cae-a8ec-43a1-99a2-d97950bcd1fe" />


- **PCB Layout**
<img width="509" height="285" alt="image" src="https://github.com/user-attachments/assets/cfbcad4d-9752-413f-9db9-ef558848d0ae" />
<img width="498" height="282" alt="image" src="https://github.com/user-attachments/assets/3555db46-a233-420b-8b1b-a16de5dd580f" />

 - **3D View**
 <img width="1068" height="568" alt="image" src="https://github.com/user-attachments/assets/e95f66fb-ff35-4d04-8867-9699e6acd1e9" />
 <img width="1070" height="571" alt="image" src="https://github.com/user-attachments/assets/500868c5-d8b4-45ac-9adf-4280b747dfb5" />

---

## 8. Disclaimer
This project is developed for educational and learning purposes only. The design has been tested to the best of the author’s knowledge; however, no guarantee is provided regarding performance or suitability for commercial or safety-critical applications. Use the design at your own risk.
Users are advised to follow proper electrical safety standards, use appropriate protective components, and verify the design thoroughly before real-world deployment

---

## 9. Author
- **Name:** SUJIT KUMAR
- **Toolchain:** KiCad EDA  









ato z
#
