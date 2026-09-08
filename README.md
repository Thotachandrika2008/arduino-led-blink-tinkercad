# Arduino LED Blink - My First Embedded Project 

🎯 **Aim:** To simulate LED blinking using Arduino Uno R3 in Tinkercad

### 🔧 Components Used
- Arduino Uno R3
- Red LED, 220Ω Resistor, Jumper Wires

### 🔌 Circuit Connection
- Pin 8 -> Resistor -> LED Anode (Long leg)
- GND -> LED Cathode (Short leg)

### 💻 Code
```cpp
void setup() {
  pinMode(8, OUTPUT);
}
void loop() {
  digitalWrite(8, HIGH);
  delay(1000);
  digitalWrite(8, LOW);
  delay(1000);
}