# EE102 Term Project: Smart Posture Monitor and AFK Alert System

This project is designed to continuously monitor user posture and activity using a Basys 3 FPGA board combined with external hardware components. 

## Key Features

- **Distance & Posture Detection:** Utilizes an HC-SR04 ultrasonic sensor to measure the distance between the user and the screen.
- **Ambient Light Sensing:** Incorporates an LDR (photoresistor) to monitor ambient lighting conditions and prevent eye strain.
- **Auditory & Visual Warnings:** Triggers an active buzzer and uses 7-segment display logic to alert the user when poor posture or prolonged AFK states are detected.
- **Finite State Machine (FSM):** Implements robust sequence detection and control logic using VHDL.

📄 Further technical details and methodology are provided in the [Final Report](emir_kucukakin_EEE102_term_project.pdf).

🎥 [Project Demo Video](https://youtu.be/zX3cPm8u5OE)
