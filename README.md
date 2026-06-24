ESP32-Based IoT Weather Monitoring System
Overview

This project is a custom-designed IoT Weather Monitoring System built around the ESP32-WROOM-32 microcontroller. The system measures environmental parameters such as temperature, humidity, and atmospheric pressure using the BME280 sensor and displays real-time data on an OLED display.

The project was designed from schematic capture to PCB layout using KiCad, demonstrating practical skills in PCB design, embedded hardware development, power management, and sensor interfacing.

Features
Real-time temperature monitoring
Relative humidity measurement
Atmospheric pressure sensing
OLED display visualization
USB-powered operation
CP2102 USB-to-UART programming interface
AMS1117-3.3V voltage regulation
Compact custom PCB design
ESP32 Wi-Fi capability for future cloud integration
Hardware Used
Microcontroller
ESP32-WROOM-32
Sensors
BME280 Environmental Sensor
Display
0.96" OLED Display (I²C)
Communication
CP2102 USB-to-UART Converter
Power Section
AMS1117-3.3 Voltage Regulator
Additional Components
Boot Push Button
Reset Push Button
Status LED
Programming Header
Decoupling Capacitors
Pull-up Resistors
PCB Design Features
Two-layer PCB
Ground plane implementation
USB interface integration
Proper power distribution
I²C communication routing
Programming and debugging header
Compact component placement
Software Used
KiCad 9
ESP-IDF / Arduino IDE
GitHub
Learning Outcomes
Schematic Design
PCB Layout Design
ESP32 Hardware Integration
Power Supply Design
USB-UART Communication
I²C Sensor Interfacing
Design Rule Checking (DRC)
PCB Manufacturing Preparation
Future Improvements
Cloud Data Logging
Mobile Dashboard
Battery Management System
Enclosure Design
OTA Firmware Updates
