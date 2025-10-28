# Industrial IoT 20-Channel Actuator Controller Board

**Industrial mixed-signal embedded design** represents one of the most demanding areas of hardware engineering — combining **digital communication**, **analog signal conditioning**, and **power electronics** into one reliable and scalable platform.  

The goal of this project is **Research & Development (R&D)** — serving as a complete **industrial IoT actuator control system** designed and implemented entirely from scratch using professional design practices.

This board integrates several critical subsystems:  
- **ESP32 MCU** for control, processing, and connectivity  
- **Ethernet PHY** for wired industrial communication  
- **12V → 5V Buck converter** for stable power regulation  
- **Relay & connector interfaces** for 12V actuator control  
- **Mixed-signal domain separation** for signal integrity and reliability  

---

## Features

### Power Supply & Regulation
- 12V input with onboard **buck converter** to 5V and 3.3V rails  
- Designed for low noise and high efficiency  
- Optimized **Power Delivery Network (PDN)** for mixed-signal domains  

### Microcontroller
- **ESP32** as the main MCU, providing dual-core performance, Wi-Fi, and Bluetooth  
- Supports both **Ethernet (via )** and wireless communication for flexibility  

### Ethernet Connectivity
- ** Ethernet PHY** integrated for deterministic industrial networking  
- Supports TCP/IP stack offload and stable long-distance communication  

### Actuator Interface
- **20-channel control** for 12V actuators using industrial-grade relays and connectors  
- Designed for modular scalability and robust operation in industrial environments  

### Mixed-Signal Design
- Careful domain separation between power, analog, and digital circuits  
- Grounding, filtering, and isolation techniques applied for EMI/EMC robustness  

---

## PCB Design Overview

This board was developed using **KiCad**, following a complete professional hardware design flow:  
1. **System-level analysis & component selection**  
2. **Schematic capture and ERC validation**  
3. **Component sizing and footprint verification**  
4. **Placement optimization** for power, signal, and thermal performance  
5. **Routing of mixed-signal domains** ensuring clean return paths and minimal noise  

### PCB Stack-Up (2-Layer Design)

This board uses a **2-layer PCB** layout optimized for cost, manufacturability, and industrial robustness.

| Layer | Description |
|--------|--------------|
| **Top Layer** | High-speed digital, power routing, and sensitive signal traces |
| **Bottom Layer** | Solid ground plane and low-speed signal routing |

This configuration maintains signal integrity while ensuring an efficient grounding strategy across digital and power sections.

---

## Industrial Design Considerations

This project applies **real-world industrial design experience** to ensure professional-grade reliability:

- **Reliable Ethernet communication** in noisy environments  
- **Proper isolation** between control and load circuits  
- **Optimized relay driver design** for safety and thermal performance  
- **ESD & surge protection** on all I/O interfaces  
- **Connector placement** for practical wiring and maintenance  

---

## R&D Methodology

The design process followed a full **Research & Development workflow**, involving:  
- Circuit simulation and validation  
- Power and thermal analysis  
- Iterative component selection and footprint verification  
- Design reviews and schematic cross-checks  

This ensures not only functionality but **industrial reliability** and **scalability** for real-world actuator control applications.

---

## Applications

- Industrial IoT actuator control systems  
- Factory automation and process control  
- Smart agriculture and remote equipment management  
- Prototyping platform for IIoT communication testing  
- Educational and research reference for mixed-signal design  

---

## Future Work

Planned improvements and next steps include:  
- Completing **PCB routing and DRC validation**  
- PDN and thermal simulation for improved efficiency  
- **Firmware development** for ESP32 once the board is fabricated — focusing on:  
  - Initial hardware **bring-up and testing**  
  - Communication testing via **Ethernet and Wi-Fi**  
  - Relay control validation and signal integrity checks  
- Integration with **MQTT / Modbus / Ethernet protocols**  
- Enhanced relay driver protection and modular expansion  

---

## Contribution & Feedback

Feedback, ideas, and technical discussions are always welcome!  
Feel free to open an issue or contribute to improving the design.

---

## 📬 Contact

**abdelrahmankh2025@gmail.com**  
