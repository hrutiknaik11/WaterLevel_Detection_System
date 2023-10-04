# Water Detection System

## Introduction

Welcome to the Water Detection System project! 
This system is designed to provide continuous water level measurements using an ultrasonic sensor, enabling users to monitor water levels in a tank. 
Additionally, it allows users to control the flow of water remotely. 
The collected data is transmitted to a central Arduino unit via radio waves and further sent to the user's phone using Bluetooth technology. 
In cases where the water level reaches a predefined threshold value, the system takes automatic action to start or stop the water pump via a relay.

## System Overview

- **Ultrasonic Sensor:** Measures the water level in a tank and sends data to the central Arduino unit.
- **Radio Waves:** Data from the ultrasonic sensor is transmitted wirelessly to the central Arduino unit.
- **Bluetooth:** The central Arduino unit sends water level and control data to the user's phone via Bluetooth.
- **Relay:** Controls the water pump/motor based on predefined threshold values.

## Components

- Arduino microcontroller units (MCUs)
- Ultrasonic sensor
- Radio wave transmitter and receiver
- Bluetooth module
- Relay for motor control
- Power supply unit
- Tank for water storage
- Smartphone with a dedicated app for data monitoring and control

## Data Transmission

Data collected by the ultrasonic sensor is sent to the central Arduino unit using radio waves. 
The central Arduino unit processes this data and transmits it to the user's smartphone via Bluetooth. 
Users can access real-time water level measurements and control the water pump/motor remotely through a dedicated mobile app.

## Threshold-Based Control

The Water Detection System includes a threshold-based control mechanism. 
If the water level reaches a certain threshold value, the relay is activated to either start or stop the water pump/motor, ensuring efficient water management.

## Requirements

- Arduino microcontroller units
- Ultrasonic sensor
- Radio wave transmitter and receiver modules
- Bluetooth module
- Relay
- Power supply unit
- Smartphone with the dedicated mobile app

## Usage

1. Install the Water Detection System components as per the provided instructions.

2. Download and install the dedicated mobile app on your smartphone.

3. Launch the mobile app and connect it to the central Arduino unit via Bluetooth.

4. Monitor real-time water level measurements and control the water pump/motor remotely.

## Contributing

Contributions to this project are welcome! If you'd like to enhance or fix issues in this system, please fork the repository, make your changes, and submit a pull request.
