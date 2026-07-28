# Temperature Alert System

## Aim

To detect temperature using a TMP36 sensor and indicate high temperature by turning ON an LED.

## Components

- Arduino UNO
- TMP36 Temperature Sensor
- LED
- 220Ω Resistor

## Connections

TMP36 Left Pin → 5V

TMP36 Middle Pin → A0

TMP36 Right Pin → GND

LED Anode → 220Ω Resistor → D8

LED Cathode → GND

## Working

The TMP36 continuously measures temperature.

If the temperature exceeds 30°C, the LED turns ON.

If the temperature falls below or equal to 30°C, the LED turns OFF.

## Expected Output

Temperature ≤ 30°C → LED OFF

Temperature > 30°C → LED ON

## Platform

Arduino UNO

Tinkercad

## Author

Merlyn Antony