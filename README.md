# Dial-a-Dose-w-Blynk
8 peristaltic pumps controlled by Arduino Mega via Blynk

Each pump circuit is a simple TIP120 circuit as depicted on https://www.arduino.cc/en/Tutorial/TransistorMotorControl
I added a 1k resistor between digital pin and transistor gate.  Inside Arduino project case, and also inside the dosing pump unit, 
I used 10wire ribbon, with 1 lead removed totaling 9.  I soldered each wire to a right angle pin, and the other 9 clamped into a DP9 
connecter.  Then any average length of DB9 cable can be used between the project case and the unit module.
