Automatic Gate Demo Kit
This project demonstrates an Arduino-based automatic gate system using an Arduino Uno. The system controls a servo motor, LEDs, and a buzzer based on input from an ultrasonic sensor to simulate a gate that opens and closes automatically.

Features
Ultrasonic Sensor: Measures distance to detect objects within a set threshold.
Servo Motor: Opens the gate (rotates to 90°) when an object is detected and closes it (rotates back) after 5 seconds.
LED Indicators:Red LED lights when the gate is closed.
Blue LED lights when the gate is open.
Buzzer: Beeps continuously while the gate is open.

Hardware Requirements
Arduino Uno
Ultrasonic Sensor (e.g., HC-SR04)
Servo Motor
Red and Blue LEDs
Buzzer
Resistors and jumper wires

Code Overview
The Arduino code:
Reads distance from the ultrasonic sensor.
Controls the servo to open/close the gate based on the distance threshold.
Manages LED states (Red for closed, Blue for open).
Activates the buzzer during gate open state.

Setup
Connect the hardware components to the Arduino Uno as per the pin configuration in the code.
Upload the Arduino code to the board using the Arduino IDE.
Test the system by placing an object within the sensor's threshold distance.

Repository Contents
AutomaticGate.ino: Main Arduino sketch for the Automatic Gate Demo Kit.
