# Self Balancing Robot - Arduino

## Description
Arduino-based self-balancing robot using MPU6050 for tilt sensing and PID control for stability. Data is processed via a complementary filter to calculate the tilt angle. L298N motor driver controls the motors via PWM.

## Required Libraries
- PID_v1
- I2Cdev
- MPU6050

## How to Install
1. Download and install Arduino IDE.
2. Install the required libraries via Arduino IDE Library Manager or manually.
3. Open `Self_Balancing_Robot.ino` in Arduino IDE.
4. Select your board (Arduino Uno) and correct COM port.
5. Upload the sketch.
