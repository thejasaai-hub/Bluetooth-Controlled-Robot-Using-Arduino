# Bluetooth-Controlled-Robot-Using-Arduino

This project demonstrates a simple Bluetooth-based control system for a robot. Using commands sent via Bluetooth, the robot's motors can be controlled to move forward, backward, turn left, turn right, or stop. The status of the robot's movement is displayed in real-time on a 16x2 I2C LCD display.

## Features
- Control robot movements via Bluetooth commands:
  - `1` for Forward
  - `2` for Backward
  - `3` for Right
  - `4` for Left
  - `5` for Stop
- Real-time status updates displayed on the LCD.

## Code Overview
The code is written for an Arduino Uno and utilizes the following components:
- **SoftwareSerial**: For Bluetooth communication.
- **LiquidCrystal_I2C**: For controlling the LCD display.
- **Motor Control Pins**: Connected to four digital pins on the Arduino to control two motors.

## Requirements
- Arduino Uno
- HC-05 Bluetooth module
- I2C 16x2 LCD display
- L298N Motor Driver or similar
- Two DC motors
- Power source

## How to Use
1. Upload the provided Arduino code to your Arduino Uno.
2. Pair the HC-05 Bluetooth module with a Bluetooth-enabled device.
3. Use a Bluetooth terminal app to send commands (`1`, `2`, `3`, `4`, `5`).
4. Observe the robot's movements and the corresponding messages on the LCD.

## License
This project is open-source and free to use.
