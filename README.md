# ESP32 Environmental Monitoring PCB

Custom PCB designed in KiCad using the ESP32-WROOM-32 microcontroller, BME280 environmental sensor, OLED display, USB programming interface, and onboard power regulation for real-time environmental monitoring.

# ESP32 Environmental Monitoring PCB

## Overview

This project is a custom-designed IoT environmental monitoring system developed using the ESP32-WROOM-32 microcontroller and implemented as a custom PCB in KiCad.

The system measures temperature, humidity, and atmospheric pressure using the BME280 sensor and displays the measured values on an OLED display. The ESP32 processes sensor data and can be expanded to support Wi-Fi connectivity for cloud monitoring and IoT applications.

The project was created to gain hands-on experience in embedded hardware design, schematic capture, PCB layout design, routing, power supply design, ESP32 programming interface integration, design rule checking, and manufacturing file generation.

## Components Used

- ESP32-WROOM-32 Microcontroller Module
- BME280 Temperature, Humidity & Pressure Sensor
- OLED Display (I2C Interface)
- CP2102 USB-to-UART Converter
- AMS1117-3.3V Voltage Regulator
- USB Micro Connector
- Programming Header (1x6 Pin)
- Reset Push Button
- Boot Push Button
- Status LED
- Resistors
- Capacitors

## Working Principle

The system is powered through a USB Micro connector.

The AMS1117 voltage regulator converts the USB 5V supply into a stable 3.3V supply required by the ESP32 and BME280 sensor.

The BME280 sensor communicates with the ESP32 through the I2C interface and continuously provides environmental data including:

- Temperature
- Humidity
- Atmospheric Pressure

The OLED display receives data through the same I2C bus and presents real-time readings to the user.

The CP2102 USB-to-UART converter enables firmware uploading and serial communication between the ESP32 and a computer.

Reset and Boot buttons are included to support ESP32 programming and debugging operations.

## Features

- Real-time Temperature Monitoring
- Real-time Humidity Monitoring
- Atmospheric Pressure Measurement
- OLED Display Interface
- USB Programming Support
- Onboard 3.3V Power Regulation
- Compact Custom PCB Design
- Expandable for Wi-Fi and IoT Applications

## Design Tools

- KiCad 9.0
- ESP32 Development Framework
- Arduino IDE / ESP-IDF

## PCB Design Process

1. Schematic Design
2. Component Selection
3. Footprint Assignment
4. Electrical Rule Check (ERC)
5. PCB Layout Design
6. Component Placement Optimization
7. Routing and Grounding
8. Design Rule Check (DRC)
9. 3D PCB Verification
10. Gerber File Generation

## Project Images

### Schematic
(Add schematic screenshot here)

### PCB Layout
(Add PCB layout screenshot here)

### 3D PCB View
(Add 3D PCB screenshot here)

## Learning Outcomes

- ESP32 Hardware Design
- I2C Communication Implementation
- Sensor Interfacing Techniques
- USB-UART Programming Circuit Design
- Power Supply Design using AMS1117
- Schematic Capture using KiCad
- PCB Component Placement
- PCB Routing and Ground Plane Design
- ERC and DRC Validation
- Gerber File Generation for Manufacturing

## Applications

- Environmental Monitoring Systems
- Smart Home Automation
- Weather Stations
- IoT Sensor Nodes
- Industrial Monitoring Systems
- Embedded Systems Learning Platform

## Future Improvements

- Wi-Fi Cloud Dashboard Integration
- Data Logging using SD Card
- Battery Backup Support
- Mobile Application Interface
- Air Quality Monitoring Sensors
- MQTT-Based IoT Connectivity


<img width="960" height="600" alt="2026-06-24 (7)" src="https://github.com/user-attachments/assets/878711e4-2d9d-486d-adb4-40e7d9ebf311" />

<img width="960" height="600" alt="2026-06-24 (8)" src="https://github.com/user-attachments/assets/3d2db83a-af8d-4f35-8d22-1040f2b038c2" />
<img width="960" height="600" alt="2026-06-24 (1)" src="https://github.com/user-attachments/assets/5cbe3688-9b80-4340-9d56-380dd9a4770d" />



## Author

**Naveen Raja R**  
B.E. Electronics and Communication Engineering  
PCB Design Enthusiast | Embedded Systems | IoT Hardware Development
