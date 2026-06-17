# Moisture Detection in Electronic Devices

## About the Project
This project is a simple Arduino-based humidity monitoring system made to detect moisture levels around electronic devices. High humidity can damage electronic components by causing corrosion, short circuits, and reduced device life.

To solve this problem, we used a DHT11 humidity sensor with an Arduino Uno to monitor humidity levels in real time. An LED indicator turns ON whenever the humidity crosses a set limit, giving a quick warning about high moisture conditions.

This project helped us understand embedded systems, sensor interfacing, Arduino programming, and real-time monitoring.

## Block diagram
![Block diagram]("C:\Pictures\new.png")

## Circuit Diagram

![Circuit Diagram](Screenshot 2025-10-11 085016.png)

## Features
- Real-time humidity detection
- Arduino and DHT11 sensor interfacing
- LED alert for high humidity
- Simple and low-cost setup
- Easy to build and understand
- Useful for environmental monitoring


## Components Used
- Arduino Uno
- DHT11 Sensor
- LED
- 5.6kΩ Resistor
- Breadboard
- Jumper Wires
- USB Cable


## How It Works
1. The DHT11 sensor measures humidity and temperature from the surrounding air.
2. The sensor sends data to the Arduino Uno.
3. Arduino processes the readings and displays them on the Serial Monitor.
4. If humidity becomes higher than the set threshold value, the LED turns ON as an alert.


## Applications
- Protection of electronic devices
- Humidity monitoring
- Educational Arduino projects
- Industrial and environmental monitoring


## Technologies Used
- Arduino IDE
- Embedded Systems
- Sensor Interfacing
- Real-Time Monitoring


## Future Improvements
- IoT and cloud monitoring
- Mobile app notifications
- Buzzer alert system
- Data logging
- Compact PCB design

- PCB-based compact design

