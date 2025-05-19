# classroomAssistant
This GitHub repository contains the code and documentation for a student-built humanoid robot designed to assist students who are unable to attend school in person. 
# Classroom Assistant – Humanoid Robot for Remote Participation

This repository contains the code, wiring diagrams, and documentation for a humanoid robot designed to help students attend class remotely when they are unable to be physically present. The project is based on the open-source InMoov model and utilizes two Arduino Nano ESP32 boards for remote control and servo management.

## 🔧 Features

- Head and eye movement via servo motors
- Remote control over Wi-Fi using one board as Master and one as Slave
- Video and audio communication through Microsoft Teams
- LED indicator for "raise hand" feature
- Modular and easy-to-expand design

## 📦 Hardware Required

- 2× Arduino Nano ESP32
- Servo motors (for eyes and neck)
- Logitech webcam with microphone and speaker
- Power supply (external recommended for motors)
- LED and resistor
- Breadboard and jumper wires
- Wi-Fi connection

## 🔌 Wiring Diagram

Check the `/diagrams` folder for the full schematic of Master and Slave boards.

## 🧠 Software Setup

1. Install the [Arduino IDE](https://www.arduino.cc/en/software)
2. Add the ESP32 board via the board manager
3. Install necessary libraries:
   - `WiFi.h`
   - `Servo.h`
4. Upload `master.ino` to the Master board
5. Upload `slave.ino` to the Slave board

## 🌐 Network Configuration

Both boards must connect to the same Wi-Fi network. The Master sends commands via web interface, and the Slave receives and executes them.

## 🚀 How to Use

1. Power on both boards.
2. Access the Master board’s IP address in a browser to send commands.
3. Use Microsoft Teams for video conferencing alongside robot control.

## 📷 Demo

*Coming soon: Link to video demo*


