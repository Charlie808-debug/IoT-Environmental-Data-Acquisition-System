# IoT-Environmental-Data-Acquisition-System
A low-cost IoT environmental monitoring system built using the **ESP32** that measures atmospheric conditions using multiple sensors and hosts a real-time web dashboard over Wi-Fi.

---

## 💻 Tech Stack

**Embedded:** ESP32, Arduino IDE, Embedded C

**Sensors:** BMP280, APDS9930, Analog UV Sensor

**Interfaces:** I²C, ADC

**Communication:** Wi-Fi

**Software:** HTML, CSS, JavaScript

**Hardware:** ADS1115, Breadboard, Jumper Wires

---

## Overview

This project was developed as part of the **Electronics System Design Laboratory** under the guidance of **Dr. Amit Kumar** at **Pandit Deendayal Energy University (PDEU)**.

The objective was to design a compact, low-power, high-precision environmental monitoring system capable of acquiring real-time micro-climate data using an ESP32-based embedded platform. The system combines multiple MEMS sensors, precision analog-to-digital conversion, and Wi-Fi connectivity to provide continuous environmental monitoring through a browser-accessible dashboard.

Designed as a team project by **Dhruvi Singh**, **Preet D. Desai**, and **Kevin Shah**, the system demonstrates the integration of embedded systems, IoT networking, sensor interfacing, and web technologies into a single real-world application.

---

## Key Features

- Real-time environmental monitoring
- ESP32-based embedded IoT platform
- High-precision sensor data acquisition
- Wi-Fi enabled asynchronous web dashboard
- Continuous monitoring with 2-second sampling interval
- External 16-bit ADC for accurate UV measurements
- Browser-based dashboard accessible without cloud services
- Low-latency wireless telemetry
- Modular and low-power embedded architecture

---

## 🛠 Hardware Components

- ESP32 Development Board
- BMP280 Temperature & Barometric Pressure Sensor
- APDS9930 Ambient Light Sensor
- Analog UV Sensor
- ADS1115 16-bit Analog-to-Digital Converter
- Breadboard
- Jumper Wires
- USB Power Supply

---

##  Environmental Parameters

The system continuously measures:

- 🌡 Temperature
- 🌍 Atmospheric Pressure
- ☀ UV Irradiance
- 💡 Ambient Light Intensity (Lux)

---

## ⚙ System Workflow

1. ESP32 initializes all connected sensors.
2. Environmental parameters are sampled every **2 seconds**.
3. Analog UV measurements are digitized using the ADS1115 16-bit ADC.
4. Sensor readings are processed locally on the ESP32.
5. An asynchronous HTTP server hosts a real-time monitoring dashboard.
6. Users connected to the same Wi-Fi network can access live environmental data through any web browser.
---

## 🎯 Engineering Highlights

- Improved UV sensing accuracy using an external **ADS1115 16-bit ADC**, overcoming the ESP32's built-in ADC limitations.
- Designed an asynchronous web server for responsive real-time visualization.
- Achieved low-latency Wi-Fi communication between the embedded device and dashboard.
- Developed a compact, low-power architecture suitable for continuous environmental monitoring.

---

## 📁 Repository Structure

```
Environmental-Monitoring-System/
│
├── docs/
│   └── Project_Report.pdf
│
├── images/
│
├── firmware/
│   └── README.md
│
└── README.md
```

---

## 📸 Project Screenshots

Add screenshots here:

- Hardware setup
- Circuit diagram
- Web dashboard
- Sensor output

---

## 🚀 Applications

- Smart Agriculture
- Greenhouse Automation
- Hyper-local Weather Monitoring
- Industrial HVAC Monitoring
- Occupational UV Safety Monitoring
- Environmental Data Collection
- Smart Campus and Smart City Deployments

---

## 📈 Project Outcome

The developed system successfully demonstrated:

- Stable long-duration operation
- Accurate environmental sensing
- Reliable Wi-Fi communication
- Real-time dashboard visualization
- Efficient embedded hardware integration

The project showcases practical implementation of embedded systems, MEMS sensor interfacing, IoT networking, and real-time environmental data acquisition.

---

## 📚 Documentation

The repository contains the complete project report including:

- Design methodology
- Hardware architecture
- Sensor interfacing
- Working principle
- System workflow
- Experimental results
- Conclusions

---

## ⚠ Firmware

The original Arduino firmware is currently unavailable.

This repository preserves the complete project documentation, hardware design, implementation methodology, and project report.

---

## Contributors

Developed by:

- **Dhruvi Rakeshkumar Singh**
- **Preet D. Desai**
- **Kevin Shah**

**Course:** Electronics System Design Laboratory

**Institution:** Pandit Deendayal Energy University (PDEU)

---

## ⭐ If you found this project useful, consider starring the repository.
