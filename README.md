# ESP32-LED-Blink
ESP32 LED Blink project using Wokwi simulation
## Components Used

- ESP32 DevKit
- Red LED
- 1kΩ Resistor

## Connections

- GPIO 2 → Resistor → LED Anode
- LED Cathode → GND

## Code

```cpp
#define LED_PIN 2

void setup() {
  pinMode(LED_PIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_PIN, HIGH);
  delay(1000);
  digitalWrite(LED_PIN, LOW);
  delay(1000);
}
## Wokwi Simulation

[Open Wokwi Simulation](https://wokwi.com/projects/4768291116716954625)
