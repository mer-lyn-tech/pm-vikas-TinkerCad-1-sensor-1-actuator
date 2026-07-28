# Light Intensity Alarm

## Aim

To detect low light intensity using a photoresistor (LDR) and activate a buzzer when it becomes dark.

## Components Used

- Arduino UNO
- Photoresistor (LDR)
- 10kΩ Resistor
- Piezo Buzzer
- Breadboard
- Jumper Wires

## Circuit Connections

### Photoresistor (LDR)

- One Leg → Arduino 5V
- Other Leg → Arduino A0
- 10kΩ Resistor between A0 and GND

### Piezo Buzzer

- Positive (+) → Arduino D8
- Negative (-) → Arduino GND

## Working

The Arduino continuously reads the light intensity from the LDR.

- When the light level is low (dark), the buzzer turns ON.
- When the light level is high (bright), the buzzer turns OFF.

## Expected Output

- Dark → Buzzer ON
- Bright → Buzzer OFF

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony