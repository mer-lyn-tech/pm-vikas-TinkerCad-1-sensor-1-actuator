# Force Sensor Controlled LED

## Aim

To detect pressure using a Force Sensitive Resistor (FSR) and turn ON an LED when pressure is applied.

## Components Used

- Arduino UNO
- Force Sensitive Resistor (FSR)
- LED
- 10kΩ Resistor
- 220Ω Resistor
- Breadboard
- Jumper Wires

## Circuit Connections

### Force Sensor

- Pin 1 → Arduino 5V
- Pin 2 → Arduino A0
- 10kΩ Resistor between A0 and GND

### LED

- Arduino D8 → 220Ω Resistor → LED Anode
- LED Cathode → Arduino GND

## Working

The Arduino reads the analog value from the FSR.

- If pressure is detected, the LED turns ON.
- If no pressure is detected, the LED turns OFF.

## Expected Output

Pressure Applied → LED ON

No Pressure → LED OFF

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony