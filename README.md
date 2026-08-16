# High-Altitude Flight Control Computer (FCC / UKB)

This repository contains the complete hardware design, schematic diagrams, and documentation for a high-altitude sounding rocket flight control computer (FCC).

---

## 📸 Hardware Overview

<p align="center">
  <img src="2025%20yüksek%20irtifa%20top_removed.png" alt="Flight Computer PCB" width="700">
</p>

---

## 🛠️ Key Technical Specifications

* **PCB Architecture:** 4-Layer Stackup (Optimized for RF & Signal Integrity)
* **Microcontroller (MCU): STM32F446RET6
* **RF Communication:** Long-range telemetry module (E22400T37S)
* **Navigation & Sensors:**
  * BMI088
  * BME280
  * L86 GNSS
* **Interfaces & Protocols:** SPI, I2C, UART
* FT232RNL UART-USB interface
* W25Q256JVFIQ SPI Flash
* MAX3232EIDR RS232 to UART converter
* INA139NA Voltage and Current Sense
* **Power Management:** Buck Converters and LDOs
* **Pyro / Recovery Channels:** High Side Drivers

---

## 📁 Repository Structure

```text
├── Altium PROJECT/        # Altium Designer project files (.PrjPcb, .PrjPcbStructure)
├── Altium SCHEMATIC/      # Detailed schematic sheets (.SchDoc)
├── 2025_UKB.pdf           # Complete hardware documentation & schematic export
└── README.md              # Project overview and technical summary
