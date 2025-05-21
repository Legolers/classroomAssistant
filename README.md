# 🤖 Classroom Assistant – Humanoid Robot for Remote Participation

This GitHub repository contains the code and documentation for a student-built humanoid robot designed to assist students who are unable to attend school in person. The project is based on the open-source **InMoov** model and utilizes a single **Arduino Nano ESP32** board with an embedded web server for wireless control.

## 🔧 Features

- 🎥 Head and eye movement via servo motors
- 🌐 Remote control through a web browser using embedded web server (no external app needed)
- 🔊 Real-time video and audio communication via Microsoft Teams
- 💡 LED "raise hand" feature for classroom interaction
- 🧩 Modular and expandable design

## 📦 Hardware Required

- 1× Arduino Nano ESP32
- Servo motors (for eyes and neck)
- Logitech webcam with built-in microphone and speaker
- Power supply (external for motors)
- LED + resistor
- Breadboard and jumper wires
- Wi-Fi network access

## 🔌 Wiring Diagram

Check the `/diagrams` folder for full schematic of motor and LED wiring to the ESP32 board.

## 🧠 Software Setup

1. Install the [Arduino IDE](https://www.arduino.cc/en/software)
2. Add the ESP32 board using the board manager
3. Install required libraries:
   - `WiFi.h`
   - `Servo.h`
4. Upload the provided `web_server_control.ino` sketch to your ESP32
5. Connect the board to the same Wi-Fi as the controlling device

## 🚀 How to Use

1. Power on the Arduino Nano ESP32
2. Open the serial monitor to find the assigned IP address
3. Open the IP address in your browser
4. Control the robot’s servos and LED through the web interface
5. Use Microsoft Teams (on a separate PC/tablet) for video conferencing

## 🎓 Educational Goals

- Promote inclusive education for homebound students
- Combine robotics and real-time web technologies
- Encourage problem-solving and innovation through hands-on learning

## 📷 Demo & Media

- 🎬 [Video Demo]() *(coming soon)*
- 📸 [Project Photos]() *(coming soon)*

## 🔗 Resources

- 🏫 School: *Ι. Μ. Παναγιωτόπουλος*



