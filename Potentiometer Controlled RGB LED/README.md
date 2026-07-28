# Potentiometer Controlled RGB LED

## Aim

To control the brightness of an RGB LED using a potentiometer.

## Components Used

- Arduino UNO
- Potentiometer
- RGB LED (Common Cathode)
- Three 220Ω Resistors
- Jumper Wires

## Circuit Connections

### Potentiometer

- Left Pin → Arduino 5V
- Middle Pin → Arduino A0
- Right Pin → Arduino GND

### RGB LED

- Red Pin → D9 through 220Ω resistor
- Green Pin → D10 through 220Ω resistor
- Blue Pin → D11 through 220Ω resistor
- Common Cathode → Arduino GND

## Working

The Arduino reads the potentiometer value and adjusts the brightness of the RGB LED. Rotating the potentiometer changes the LED brightness.

## Expected Output

- Rotate left → Low brightness
- Rotate right → High brightness

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony