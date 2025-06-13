# Blinking-LED
# Lesson 01 - Blinking LED 

 Objective
Learn to blink an LED using Arduino UNO —  embedded system project!

Components
- 1x Arduino UNO R3
- 1x 220Ω resistor
- 1x LED (any color)
- 1x Breadboard
- 2x Jumper wires
- USB cable


 Wiring
- Pin 13 → LED anode (long leg)
- LED cathode (short leg) → Resistor → GND

Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);  // turn LED on
  delay(1000);             // wait 1 second
  digitalWrite(13, LOW);   // turn LED off
  delay(1000);             // wait 1 second
}
