# Self-Balancing Robot Project

This project involves the creation of a self-balancing robot using an Arduino microcontroller, PID control, and an MPU6050 sensor. The robot stabilizes itself using feedback from the MPU6050 to maintain balance, simulating the dynamics of an inverted pendulum.

## Features

- **PID Control:** Implements a PID controller to balance the robot based on real-time feedback.
- **MPU6050 Integration:** Utilizes the MPU6050 sensor to measure orientation (yaw, pitch, roll).
- **Custom Motor Control:** Employs an L298N motor driver to control the DC motors responsible for movement.
- **Real-Time Processing:** Adjusts motor speeds dynamically to maintain the robot's balance.

## Components

- **Arduino UNO**
- **MPU6050 Sensor**
- **L298N Motor Driver**
- **DC Motors and Wheels**
- **Steel Rods and Plates for Structure**

## Setup

1. **Wiring:** Connect the MPU6050, L298N motor driver, and motors as per the schematic provided.
2. **Code:** Upload the provided Arduino code (`SelfBalancingRobot.ino`) to the Arduino UNO.
3. **Calibration:** Calibrate the MPU6050 sensor to ensure accurate orientation readings.

## How It Works

1. **Data Acquisition:** The MPU6050 sensor continuously measures the robot's orientation.
2. **PID Control:** The PID controller processes the orientation data to determine the required motor adjustments.
3. **Motor Adjustment:** The motor speeds are adjusted to correct the robot's tilt and maintain balance.

## Usage

- **Power On:** Connect the power supply to the Arduino and motors.
- **Real-Time Adjustment:** The robot will automatically attempt to balance itself. Fine-tuning of PID parameters may be necessary for optimal performance.

## Troubleshooting

- **Robot Not Balancing:** Ensure correct wiring and verify the MPU6050 is properly calibrated.
- **Unstable Movement:** Adjust the PID parameters for better stability.

## Future Improvements

- **Enhanced Stability:** Experiment with different PID settings and motor configurations.
- **Advanced Features:** Add additional sensors or remote control functionality.
