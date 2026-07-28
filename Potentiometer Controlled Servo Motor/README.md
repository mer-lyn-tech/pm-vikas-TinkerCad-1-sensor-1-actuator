# Potentiometer Controlled Servo Motor

## Aim

To control the angle of a servo motor using a potentiometer.

## Components Used

- Arduino UNO
- Potentiometer
- Servo Motor
- Jumper Wires

## Circuit Connections

### Potentiometer

- Left Pin → Arduino 5V
- Middle Pin → Arduino A0
- Right Pin → Arduino GND

### Servo Motor

- Red Wire → Arduino 5V
- Brown/Black Wire → Arduino GND
- Orange/Yellow Wire → Arduino D9

## Working

The Arduino reads the analog value from the potentiometer and converts it into an angle between 0° and 180°. The servo motor rotates to the corresponding angle.

## Expected Output

- Rotate knob left → Servo moves to 0°
- Rotate knob right → Servo moves to 180°

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony