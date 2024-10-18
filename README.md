NAME : VELIDANDI SAKETH REDDY
COMPANY: CODTECH IT SOLUTIONS  
ID: CT08DS8242
DOMAIN: EMBEDDED SYSTEMS   
DURATION: SEPTEMBER TO OCTOBER 2024  
MENTOR:  

OVERVIEW OF THE PROJECT 
---

Project : LED Blinking using Arduino

---

Objective:  The aim is to blink an LED using an Arduino. The code allows adjusting the LED's blink rate with a variable 'delayT' that controls the on/off timing.

---

Components Required:
1. Arduino Board (e.g., Arduino Uno)
2. LED
3. Resistor (220Ω recommended)
4. Breadboard and Jumper Wires
5. USB Cable

---

Key Concepts:
1. Digital Pin Control: The LED is controlled using digital pin 13.
2. Adjustable Timing: The blink rate can be adjusted by modifying 'delayT'.

---

Steps to Implement the Project:

Setting Up the Hardware:
1. Connect the LED’s positive leg to digital pin 13 on the Arduino.
2. Connect the negative leg to a 220Ω resistor and then to GND.

Writing the Arduino Sketch:
1. Open the Arduino IDE and use the following code:
```cpp
int LEDpin = 13;
int delayT = 1000;

void setup() {
  pinMode(LEDpin, OUTPUT);
}

void loop() {
  digitalWrite(LEDpin, HIGH);  
  delay(delayT);               
  digitalWrite(LEDpin, LOW);   
  delay(delayT);               
}
```

Uploading the Sketch:
1. Connect the Arduino to your computer via USB.
2. Select the board and port in the Arduino IDE.
3. Click "Upload" to compile and upload the sketch.

---

Observing the Output:
Once the code is uploaded, the LED will blink with a 1-second on/off interval.

---

Learning Outcomes:
- Pin Control: Learn how to control digital pins using Arduino.
- Adjustable Timing: Understand how to modify blink timing with the `delay()' function.
- Basic Sketch Uploading: Gain experience uploading Arduino sketches.
- CODETECH-TASK-1
  
