# Electrical Automation Engineer

#### Technical Skills: Altium Designer, Saturn PCB Toolkit, ISIS proteus, JTAG/SWD, VS Code, PlatformIO, STM32CubeIDE

## Education
- **National Engineering School of Gabes (ENIG)**, Electrical and Automation Engineering  
  *September 2022 - June 2025*
- **Preparatory Institute for Engineering Studies (IPEI Gabes)**, Preparatory Cycle  
  *September 2019 - June 2022*
- **Sombat High School**, Science Technology Baccalaureate  
  *June 2019*
  
## Experience
**4InA Technologie, Manouba** | End-of-Year Internship  
*February 2025 - June 2025*  
  - Designed a 4-layer PCB integrating STM32 and ESP32 microcontrollers for a modular smart meter.  
  - Developed embedded firmware for data transmission and remote control via an HTTP server.  
  - Delivered a functional prototype for industrial use.  
  - *Keywords*: Embedded Hardware, 4-layer PCB, DFM, Altium Designer, Smart Meters

  **WEMAKE 3D, Ariana** | Summer Internship  
  *June 2024 - July 2024*  
  - Developed a Human-Machine Interface for an automatic cutting device.  
  - Designed a PCB to interface sensors and motor controls.  
  - *Keywords*: HMI, PCB Design, ESP32, Git, 3D Printers

  **STEG-BTGG, Gabès** | Summer Internship  
  *July 2023*  
  - Observed gas compression and pipeline systems, gaining insight into industrial energy infrastructure.  
  - *Keywords*: Gas Compression, Pipeline Management, Energy Infrastructure

## Projects
### 🧩 Modular Motherboard for Smart Meters  
**Technologies:** STM32, ESP32, LoRa, UART, I2C, SPI, ADC, Altium Designer, Multilayer PCB, Power Management, Sensor Interfaces

As part of my end-of-year engineering project, I designed and developed a modular 4-layer PCB to serve as a central platform for smart metering and industrial sensing applications. The system combines robust data acquisition, communication, and power management to enable reliable and scalable monitoring in embedded environments.

#### 🔧 System Overview:
- **Microcontroller Architecture:**
  - STM32 handles analog signal acquisition and preprocessing (current, voltage, and environmental sensors).
  - ESP32 manages wireless communication and higher-level data handling.
  - Data exchange between STM32 and ESP32 is performed via UART using a clearly defined protocol.

- **Sensor Integration:**
  - Support for current and voltage sensors, with analog signal conditioning circuits for stable ADC readings.
  - Expandable interfaces for temperature, vibration, and other indusatrial sensors using various communication protocols.
  - Modular pin headers designed to simplify the addition of external modules or sensors.

- **Wireless Communication:**
  - Integration of a **LoRa module** for long-range, low-power data transmission which is suitable for remote monitoring use cases.
  - The ESP32 acts as a bridge between STM32 data and LoRa/cloud services.

- **PCB Design:**
  - Full **4-layer** stack-up with clear separation between analog and digital domains to reduce noise and EMI.
  - Onboard voltage regulation using LDOs, with dedicated power planes for critical components.
  - Clean routing for high-frequency signals, impedance-matched where needed, and adequate decoupling/filtering.

#### 🛠 My Contributions:
- Designed complete schematics and multilayer PCB in **Altium Designer**.
- Defined and implemented the **data flow** between microcontrollers and communication modules.
- Developed signal conditioning circuits and selected appropriate components for accurate analog sensing.
-  Performed **impedance calculations using Saturn PCB Toolkit** to ensure high-speed signal integrity and respect layout proprieties.
- Validated inter-module communication and sensor acquisition through testing routines.

> This project highlights my ability to combine embedded system design, PCB layout, and practical integration of sensing and communication technologies in a modular hardware platform.


