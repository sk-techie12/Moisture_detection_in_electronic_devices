# Moisture Detection in Electronic Devices

## Overview

Moisture and high humidity can significantly affect the performance and lifespan of electronic devices. Excess moisture may lead to corrosion, leakage currents, malfunctioning components, and reduced reliability.

This project presents a simple humidity monitoring system using an Arduino Uno and DHT11 sensor. The system continuously monitors environmental humidity and provides a visual alert using an LED whenever humidity exceeds a predefined threshold.

The project demonstrates the fundamentals of embedded systems, sensor interfacing, real-time monitoring, and Arduino programming.

---

## Problem Statement

Electronic devices operating in humid environments are vulnerable to:

- Corrosion of metallic contacts
- Leakage currents
- Reduced component lifespan
- Sensor inaccuracies
- Potential short-circuit risks due to moisture condensation

Such issues are commonly observed in:

- Coastal regions
- Industrial environments
- Laboratories
- Homes during monsoon seasons
- Storage rooms containing electronic equipment

---

## Proposed Solution

The proposed system uses a DHT11 humidity sensor connected to an Arduino Uno.

The sensor continuously measures relative humidity and sends digital data to the Arduino. When humidity rises above a predefined threshold, an LED indicator turns ON, providing an immediate warning of high-moisture conditions.

---

## Features

- Real-time humidity monitoring
- Arduino Uno and DHT11 sensor interfacing
- LED-based visual alert system
- Serial Monitor output
- Low-cost implementation
- Easy to build and understand
- Suitable for educational and monitoring applications

---

## Components Used

| Component | Quantity |
|------------|-----------|
| Arduino Uno | 1 |
| DHT11 Sensor | 1 |
| LED | 1 |
| 5.6 kΩ Resistor | 1 |
| Breadboard | 1 |
| Jumper Wires | Multiple |
| USB Cable | 1 |

---

## Circuit Connections

### DHT11 Sensor

| DHT11 Pin | Arduino Uno |
|------------|-------------|
| VCC | 5V |
| GND | GND |
| DATA | Digital Pin 4 |

### LED

| LED Pin | Arduino Uno |
|----------|-------------|
| Anode (+) | Digital Pin 8 |
| Cathode (-) | GND |

### Pull-Up Resistor

- 5.6 kΩ resistor connected between DATA and VCC of DHT11.

---

## Block Diagram

```text
Humidity Environment
          │
          ▼
      DHT11 Sensor
          │
          ▼
      Arduino Uno
          │
   ┌──────┴──────┐
   ▼             ▼
Serial Monitor   LED Alert
```

---

## Working Principle

1. The DHT11 sensor measures ambient humidity and temperature.
2. Sensor readings are transmitted digitally to the Arduino Uno.
3. Arduino processes the received data.
4. Humidity values are displayed on the Serial Monitor.
5. If humidity exceeds the threshold value (70%), the LED turns ON.
6. If humidity remains below the threshold, the LED stays OFF.

---

## Software Requirements

- Arduino IDE
- DHT Sensor Library
- Adafruit Sensor Library

---

## Installation & Setup

1. Install Arduino IDE.
2. Install the required libraries:
   - DHT Sensor Library
   - Adafruit Unified Sensor Library
3. Assemble the circuit as shown.
4. Upload the Arduino code to the Arduino Uno.
5. Open the Serial Monitor.
6. Observe humidity readings and LED status.

---

## Sample Output

```text
Current Humidity: 65%
LED Status: OFF

Current Humidity: 74%
LED Status: ON
```

---

## Applications

- Protection of electronic devices
- Environmental monitoring
- Educational Arduino projects
- Industrial humidity monitoring
- Laboratory condition monitoring
- Storage room monitoring

---

## Challenges Faced

- Ensuring stable communication between Arduino and DHT11.
- Selecting an appropriate humidity threshold value.
- Managing fluctuations in sensor readings.
- Understanding sensor interfacing and digital communication.

---

## Learning Outcomes

Through this project, we gained practical experience in:

- Arduino programming
- Embedded systems development
- Sensor interfacing
- Real-time monitoring systems
- Hardware prototyping
- Environmental sensing applications

---

## Future Improvements

- IoT-based remote monitoring
- Mobile application notifications
- Cloud data storage
- Data logging and analytics
- Buzzer-based alarm system
- LCD/OLED display integration
- PCB-based compact design
- Wireless monitoring using ESP32

---

## Project Images

### Hardware Setup

(Add hardware image here)

### Circuit Diagram

(Add circuit diagram here)

### Working Prototype

(Add prototype image here)

---

## Project Team

- Sanvee Kulkarni
- Rajwardhan Nile
- Om Patil
- Rutuja Patil

---

## References

1. Arduino Based Temperature and Humidity Sensor (2018)
2. Real Time Temperature, Humidity Monitoring & Alert System
3. Study of Low-Cost Arduino Uno Based System to Determine the Response and Recovery Times of Humidity Sensor

---

## License

This project is developed for educational and academic purposes.
- PCB-based compact design

