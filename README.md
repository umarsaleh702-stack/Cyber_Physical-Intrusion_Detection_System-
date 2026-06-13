# Cyber-Physical Intrusion Detection System

## Overview
This project presents an ultrasonic-based perimeter intrusion detection system designed to detect unauthorized entry into a protected area. The system uses ultrasonic sensors to continuously monitor the perimeter and trigger an alarm when an intrusion is detected.

## Objectives
- Detect intruders within a predefined perimeter.
- Provide real-time alerting.
- Display the distance
- Develop a low-cost and reliable security solution.

## System Components
- Ultrasonic Sensor (HC-SR04)
- Microcontroller (Esp32)
- Buzzer
- Led
- Display Unit (I2C)

## Working Principle
The ultrasonic sensor transmits high-frequency sound waves and measures the reflected echo. Any object entering the monitored area changes the measured distance, triggering an intrusion alert.

## Features
- Real-time intrusion detection
- Low-cost implementation
- Easy installation
- Expandable architecture

## Hardware Architecture
(https://github.com/umarsaleh702-stack/Cyber_Physical-Intrusion_Detection_System-/blob/main/Block_Diagram.png)

## Circuit Diagram
(https://github.com/umarsaleh702-stack/Cyber_Physical-Intrusion_Detection_System-/blob/main/Circuit_Diagram.png))

## Software Implementation
The system was programmed using Esp32. Distance measurements are continuously monitored and compared against a predefined threshold.

## Results
The system successfully detected intrusions within the monitored perimeter and generated alarm and displayed the distance.

## Future Improvements
- IoT-based remote monitoring
- Wireless communication
- Machine learning-based false alarm reduction
- Solar-powered operation

## Author
Umar Saleh Ibrahim
B.Eng. Electrical Engineering
