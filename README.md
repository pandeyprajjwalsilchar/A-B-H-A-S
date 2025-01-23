Arduino-Based Home Automation System

Overview
  This project demonstrates an IoT-enabled home automation system designed using the ESP32 microcontroller. The system integrates sensors and relays to automate household devices, providing enhanced safety, convenience, and energy efficiency.

Features
  Real-time Control: Operate lights and fans remotely via a mobile application connected to the Arduino IoT Cloud.
  Safety Features: Includes Flame IR and MQ5 gas sensors for fire and gas leakage detection.
  Scalability: Modular architecture allows integration of additional sensors and devices.
  User-Friendly Interface: Control and monitor devices through the Arduino IoT Cloud app.

Problem Statement
  Modern households demand intelligent automation systems for:
    Enhancing convenience and safety.
    Reducing energy wastage.
    Addressing affordability and customization gaps in existing solutions.

This project aims to:
  Design a low-cost, scalable IoT-based system.
  Integrate sensors for hazard detection.
  Provide remote control through a mobile application.

Components Used
  Hardware
    ESP32 Microcontroller:
    Dual-core processor with built-in WiFi and Bluetooth.
    Handles input from sensors and communicates with the Arduino IoT Cloud.
    MQ5 Gas Sensor:
      Detects combustible gases like LPG and hydrogen.
    Flame IR Sensor:
      Detects fire by sensing UV radiation at the ignition point.
    4-Channel Relay Module:
      Controls high-power devices such as lights and fans.
    LEDs:
      Simulates device operations during testing.
    Power Supply:
      Provides 3.3V/5V to the ESP32 and other components.
  Software
    Arduino IDE:
      Programming and uploading logic to the ESP32.
    Arduino IoT Cloud:
      Offers a dashboard for real-time monitoring and device control.
    Libraries:
      WiFi and MQTT libraries for efficient integration.

System Architecture
  Flow Diagram
    ...

  Block Diagram
    ...

Setup and Installation
  Hardware Setup:
    Assemble components on a breadboard.
    Connect sensors, ESP32, and relays as per the circuit diagram.
  Software Configuration:
    Install Arduino IDE and required libraries.
    Connect ESP32 to the local WiFi network.
    Set up a project on Arduino IoT Cloud and link the ESP32.
    Code Deployment:
      Write and upload the control logic to the ESP32 using Arduino IDE.
      Test and debug using LEDs.

Results
  1. The system successfully controlled LEDs via the Arduino IoT Cloud mobile app.
  2. Real-time data from sensors was processed by ESP32 and displayed on the app.
  3. The modular design proved its scalability for future expansions.

Future Scope
  1. Integration of more sensors, such as temperature and humidity.
  2. Adding support for voice control using Google Assistant or Alexa.
  3. Enhanced mobile app interface for better user experience.
