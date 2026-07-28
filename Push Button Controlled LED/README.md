# Push Button Controlled LED

## Aim

To control an LED using a push button. When the button is pressed, the LED turns ON. When the button is released, the LED turns OFF.

## Components Used

- Arduino UNO
- Push Button
- LED
- 220Ω Resistor
- Jumper Wires

## Circuit Connections

### Push Button

- One terminal → Arduino Digital Pin D2
- Opposite terminal → Arduino GND

### LED

- Arduino D8 → 220Ω Resistor → LED Anode (Long Leg)
- LED Cathode (Short Leg) → Arduino GND

## Working

The Arduino continuously reads the state of the push button using Digital Pin D2.

- If the button is pressed, the LED connected to Digital Pin D8 turns ON.
- If the button is released, the LED turns OFF.

The project uses the Arduino's internal pull-up resistor (`INPUT_PULLUP`), so no external resistor is required for the push button.

## Expected Output

- Button Pressed → LED ON
- Button Released → LED OFF

## Platform

- Arduino UNO
- Tinkercad Circuits

## Author

Merlyn Antony