# Home Automation System Using ESP32 + Blynk IoT

<p align="center">
  <img src="HomeAutomation.png" alt="Home Automation System" width="900" />
</p>

A smart home automation project built to monitor and control devices such as lights, fans, and power plugs remotely through a mobile application. The system uses a Wi-Fi-enabled microcontroller with Blynk IoT to provide an easy and scalable home automation interface.

## Overview

This project demonstrates how to create a low-cost home automation system that allows users to:

- Turn appliances ON/OFF remotely
- Control devices through a smartphone app
- Use a relay-based switching mechanism
- Integrate with IoT for remote access and monitoring
- Expand the design for more rooms, appliances, and sensors

## Features

- Wi-Fi-based device control
- Simple mobile control using Blynk
- Relay-driven switching for home appliances
- Expandable code structure for more modules
- Suitable for prototype and learning projects

## Hardware Concept

The system includes:

- ESP32 / Wi-Fi-enabled microcontroller
- Relay module for appliance switching
- Home appliances such as lights, fans, and plugs
- Blynk mobile app for remote control
- Internet connectivity through Wi-Fi

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
│   └── sketch_apr30a.ino
├── docs/
│   └── README.md
├── sketch_apr30a/
│   └── sketch_apr30a.ino   # Legacy original project source
└── .gitignore
```

## Project Status

This project is a prototype and educational implementation designed for learning and experimentation. It is a good starting point for building a more advanced smart home automation system with additional sensors, scheduling, and automation rules.

## Device States

<p align="center">
  <img src="ON%20state.jpeg" alt="Appliance ON state" width="420" />
  <img src="OFF%20state.jpeg" alt="Appliance OFF state" width="420" />
</p>

## Getting Started

1. Open the Arduino sketch in `firmware/sketch_apr30a.ino`.
2. Update your Wi-Fi credentials and Blynk authentication details.
3. Upload the code to your ESP32/ESP8266-compatible board.
4. Open the Blynk app and configure the buttons for your devices.
5. Test the ON/OFF switching for your appliances.

## Important Notes

- Ensure the correct GPIO pins are assigned in the code.
- Use your own Wi-Fi SSID and password.
- Set the correct Blynk authentication token and template values.
- The project is designed as a learning prototype and can be extended for real-world use.

## Documentation

Project documents and presentation files are included in the repository for reference and understanding.

## License

This project is intended for learning and personal use. Please make sure to credit the original author if you reuse or adapt this work.

---

Built for smart home learning and IoT experimentation.
