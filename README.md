# 6-Servo Motor Control using Arduino

This project demonstrates how to control six servo motors using an Arduino Uno. Each servo rotates from 0 to 180 degrees and then back to 0 in a continuous loop.

## Project Components

- Arduino Uno board
- 6 servo motors
- Jumper wires
- Breadboard
- Optional: External power supply

## How It Works

Each servo motor is connected to a separate digital pin on the Arduino (pins 2 to 7).  
The Arduino sketch uses the Servo library to move all six motors together from 0 to 180 degrees and back.  
The motion repeats continuously with a small delay between steps for smooth movement.

## Code Description

- The file servo_control.ino contains the Arduino code.
- The setup() function attaches each servo to a digital pin.
- The loop() function sweeps all servos forward and backward using a for-loop.

## How to Use

1. Connect each of the six servo motors to pins 2 through 7 on the Arduino.
2. Upload the servo_control.ino sketch using the Arduino IDE.
3. Power the Arduino using USB or an external power source.
4. Observe the synchronized movement of the servo motors.
