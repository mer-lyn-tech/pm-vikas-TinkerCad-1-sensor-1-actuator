# Ultrasonic Distance Alarm

## Aim

To detect nearby objects using an ultrasonic sensor and activate a buzzer when an object is within 15 cm.

## Components Used

- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Piezo Buzzer
- Jumper Wires

## Circuit Connections

### Ultrasonic Sensor

- VCC → Arduino 5V
- GND → Arduino GND
- TRIG → Arduino D9
- ECHO → Arduino D10

### Piezo Buzzer

- Positive (+) → Arduino D8
- Negative (-) → Arduino GND

## Working

The ultrasonic sensor measures the distance to an object.

- If the distance is less than 15 cm, the buzzer turns ON.
- If the distance is 15 cm or more, the buzzer remains OFF.

## Expected Output

- Distance < 15 cm → Buzzer ON
- Distance ≥ 15 cm → Buzzer OFF

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony