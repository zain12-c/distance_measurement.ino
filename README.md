# Arduino Distance Measurement System

## Overview
This project is an Arduino-based distance measurement system that uses an HC-SR04 ultrasonic sensor to calculate distance in real-time. It demonstrates basic embedded systems and sensor integration concepts.

## Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Jumper Wires
- Breadboard
- USB Cable

## Technologies
- Arduino (C++)
- Embedded Systems

## Features
- Real-time distance measurement
- Accurate and fast readings
- Simple and efficient design
- Serial monitor output display

## Circuit Connections
- VCC → 5V  
- GND → GND  
- TRIG → Pin 9  
- ECHO → Pin 10  

## How It Works
The ultrasonic sensor sends sound waves and waits for them to reflect back. The time taken for the echo is used to calculate the distance.

## How to Run
1. Open the code in Arduino IDE  
2. Connect Arduino board via USB  
3. Select Board and Port  
4. Upload the code  
5. Open Serial Monitor to view distance  

## Output
![WhatsApp Image 2026-03-26 at 12 37 48 AM](https://github.com/user-attachments/assets/5d3ec016-4023-4d7f-815a-1c8a6da9979b)

## Future Improvements
- Add LCD display for output  
- Improve measurement accuracy  
- Integrate with mobile or web application  
