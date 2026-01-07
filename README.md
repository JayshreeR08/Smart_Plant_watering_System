# Automatic Plant Watering System 🌱

## Overview
This project is an IoT-based Automatic Plant Watering System designed to water plants automatically based on soil moisture levels. The system helps conserve water and ensures plants receive the required amount of water without manual intervention.

This project was developed as part of a Project-Based Learning (PBL) course.

---

## Problem Statement
Manual plant watering often leads to overwatering or underwatering, especially when users forget or are unavailable. This system automates the process using sensors and a microcontroller to improve efficiency and plant health.

---

## Solution
The system continuously monitors soil moisture using a sensor. When the moisture level falls below a predefined threshold, the microcontroller activates a water pump to irrigate the plant. Once adequate moisture is detected, the pump is turned off automatically.

---

## Components Used
- Microcontroller (Arduino / ESP8266 / ESP32)
- Soil Moisture Sensor
- Water Pump
- Relay Module
- Power Supply
- Connecting Wires
- Plant Pot and Water Source

---

## Working Principle
1. The soil moisture sensor measures the moisture content of the soil.
2. Sensor data is sent to the microcontroller.
3. If moisture is below the threshold, the relay activates the water pump.
4. Water is supplied to the plant.
5. Once sufficient moisture is reached, the pump is turned off.

---

## Code
- Reading sensor values
- Comparing moisture threshold
- Controlling the relay and pump

---

## Applications
- Home gardening
- Greenhouses
- Smart agriculture
- Indoor plants

---

## Future Improvements
- Mobile app integration
- Weather-based watering
- IoT cloud monitoring
- Solar power support

---

## Code Explanation
The system uses an ADC pin to read analog values from a soil moisture sensor.
The sensor outputs values between 0 and 4095 depending on soil moisture.

- Higher values indicate dry soil
- Lower values indicate wet soil

A threshold value is defined to determine when the soil is dry.
Based on this threshold, an output pin controls an LED (or relay for a water pump).

---

## Hardware Setup
![Hardware Setup](images/project_setup.jpg)


## Author
Jayshree
