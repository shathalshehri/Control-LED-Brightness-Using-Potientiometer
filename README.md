# Arduino LED Brightness Control with Potentiometer

This project demonstrates how to control the brightness of an LED using a potentiometer and an Arduino board.

## Hardware Components

- Arduino board
- Potentiometer
- Breadboard
- LED
- 1K Ohm resistor
- Jumper wires

## Circuit Diagram

![Circuit Diagram](Set-Up.JPG)

## Demo

Watch the LED brightness control demo [here](https://github.com/shathalshehri/Control-LED-Brightness-Using-Potientiometer/blob/main/ControlLEDBrightnessDemo.MOV).

## Code

The code to control the LED brightness using a potentiometer can be found in the [Control_LED_Brightness_with_aPotientiometer.ino](Control_LED_Brightness_with_aPotientiometer.ino) file.

```cpp
int potPin = A0;
int potValue = 0;
int brightness = 0;
int ledPin = 6;

void setup() {
  Serial.begin(9600);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  potValue =

