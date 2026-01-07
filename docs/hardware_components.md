# Hardware Components

## Components List
1. ESP32 Development Board  
2. Soil Moisture Sensor  
3. Relay Module (5V)  
4. Mini Water Pump  
5. External Power Supply for Pump  
6. Jumper Wires  

---

## Circuit Connections

### Soil Moisture Sensor
- VCC → ESP32 3.3V  
- GND → ESP32 GND  
- AO → ESP32 GPIO 34  

### Relay Module
- VCC → ESP32 5V  
- GND → ESP32 GND  
- IN → ESP32 GPIO 25  

### Water Pump
- Pump Positive Terminal → Relay NO (Normally Open)  
- Relay COM → External Power Supply Positive  
- Pump Negative Terminal → External Power Supply Negative  

---

## Working Principle
The soil moisture sensor provides an analog output to the ESP32 based on the moisture content of the soil.  
When the moisture level drops below a predefined threshold, the ESP32 outputs a HIGH signal to the relay module, activating the water pump.  
Once sufficient moisture is detected, the ESP32 outputs a LOW signal, turning the pump OFF automatically.
