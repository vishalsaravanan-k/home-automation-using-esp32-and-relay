# 🏠 Home Automation using ESP32 with relay

This project is a basic **home automation system** built using an **ESP32**, capable of turning appliances **ON/OFF** through both **mobile app (via Wi-Fi)** and an **IR remote**. It is designed for beginners in IoT and embedded systems who want to automate devices like lights, fans, or other home appliances.

---

## 📦 Features
- ✅ Control appliances via **Wi-Fi** (mobile app/web interface)
- ✅ Support for **IR remote control** using TSOP1838 sensor
- ✅ 8-channel relay circuit for switching multiple devices
- ✅ Designed using **KiCad** and built around **ESP32-WROOM-32**
- ✅ USB-C interface with ESD protection and CH340 serial converter
- ✅ Power supply using AMS1117-3.3

---

## 🧰 Hardware Components
- ESP32-WROOM-32
- CH340C (USB to serial)
- 8 x Relays (5V)
- 8 x BC547 Transistors
- Diodes (1N4007), LEDs, Resistors
- TSOP1838 IR Receiver
- USB-C Connector
- AMS1117-3.3 Voltage Regulator

---

## 🚀 How It Works
1. ESP32 receives **IR commands** from a remote via TSOP1838.
2. Or, it receives **commands over Wi-Fi** from a mobile/web app.
3. Based on the command, the ESP32 toggles one of the 8 relay channels.
4. Each relay can be connected to an AC appliance to turn it ON or OFF.

---

