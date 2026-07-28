# Automatic Door System

## Aim

To automatically open and close a door using an ultrasonic sensor and a servo motor.

## Components

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- Servo Motor

## Connections

TRIG → D9

ECHO → D10

Servo Signal → D6

## Working

The ultrasonic sensor measures the distance to an object.

If the object is within 15 cm, the servo rotates to 90° to simulate opening a door.

When the object moves away, the servo returns to 0°, simulating a closed door.

## Expected Output

Distance < 15 cm → Door Open

Distance ≥ 15 cm → Door Closed

## Platform

Arduino UNO

Tinkercad

## Author

Merlyn Antony