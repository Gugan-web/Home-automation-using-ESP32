# Home Automation System Using ESP32 + Blynk IoT

<div align="center">
  <img src="HomeAutomation.png" alt="Home Automation System" width="900" />
</div>

<p align="center">
  <a href="#overview"><img src="https://img.shields.io/badge/ESP32-Home%20Automation-00A6FB?style=for-the-badge&logo=arduino&logoColor=white" alt="ESP32 Home Automation" /></a>
  <a href="#features"><img src="https://img.shields.io/badge/Blynk-IoT-5C6BC0?style=for-the-badge&logo=blynk&logoColor=white" alt="Blynk IoT" /></a>
  <a href="#getting-started"><img src="https://img.shields.io/badge/Status-Prototype-22C55E?style=for-the-badge" alt="Prototype Status" /></a>
</p>

A smart home automation project that enables users to remotely control and monitor household appliances through a mobile application. This project uses an ESP32-based controller connected with relays and Wi-Fi, and is integrated with Blynk IoT to provide an easy and scalable home automation solution.

## Overview

This project was designed to help automate everyday home devices such as lights, fans, and plugs. The ESP32 acts as the central controller, while relays handle switching operations and Blynk provides a simple mobile interface for remote control.

It is a compact, affordable, and beginner-friendly IoT prototype ideal for learning embedded systems, automation, and smart home design.

## Key Features

- Remote ON/OFF control of home appliances
- Wi-Fi connectivity using ESP32
- Blynk app integration for mobile control
- Relay-based switching mechanism
- Beginner-friendly architecture for smart home learning
- Expandable design for additional devices and sensors

## Hardware Concept

The system uses the following core components:

- ESP32 / Wi-Fi-enabled microcontroller
- Relay module for appliance switching
- Household devices such as lights, fans, and plugs
- Blynk mobile application for control interface
- Wi-Fi network connection for internet-based access

## Project Gallery

<div align="center">
  <img src="ON%20state.jpeg" alt="Device ON state" width="420" />
  <img src="OFF%20state.jpeg" alt="Device OFF state" width="420" />
</div>

## Repository Structure

```text
Home-automation-using-ESP32/
├── README.md
├── HomeAutomation.png
├── ON state.jpeg
├── OFF state.jpeg
├── DOC-20250514-WA0005..pdf
├── HA ppt final for pdf.pdf
├── firmware/
│   ├── README.md
│   └── sketch_apr30a.ino
├── docs/
│   └── README.md
├── sketch_apr30a/
│   └── sketch_apr30a.ino
└── .gitignore
```

## Getting Started

### Prerequisites

- Arduino IDE or PlatformIO
- ESP32 board support installed
- Blynk IoT app installed on your smartphone
- Wi-Fi network credentials
- Relay module and basic home appliance wiring

### Steps

1. Open the firmware file in `firmware/sketch_apr30a.ino`.
2. Update the Wi-Fi SSID and password.
3. Add your Blynk authentication token.
4. Connect the ESP32 to the relay and appliance circuit.
5. Upload the code to the microcontroller.
6. Open the Blynk app and control the devices remotely.

## Configuration

Before uploading the code, update the following values in the firmware:

```cpp
char ssid[] = "your_wifi_name";
char pass[] = "your_wifi_password";
#define BLYNK_AUTH_TOKEN "your_auth_token"
```

Also verify that the GPIO pins used for relays match the actual wiring in your project.

## Important Notes

- Ensure the correct pins are assigned for the relay connections.
- Use a proper power supply for the ESP32 and relay module.
- This project is intended as a learning and prototype system.
- For production use, add safety protections, hardware isolation, and better error handling.

## Documentation

Project-related documents and presentation files are included in the repository for reference and understanding.

- `DOC-20250514-WA0005..pdf`
- `HA ppt final for pdf.pdf`

## Future Improvements

This project can be expanded with:

- Multiple relay channels
- Sensor-based automation
- Scheduling and timers
- Mobile notifications
- Energy monitoring
- Web dashboard integration

## License

This project is intended for educational and personal use. Please give appropriate credit if you reuse or adapt the project design.

---

<p align="center">
  <strong>Built for smart-home learning, IoT experimentation, and embedded systems exploration.</strong>
</p>

