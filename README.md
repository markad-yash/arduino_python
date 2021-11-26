
# Libraries for Arduino to Communicate with Python 

1. Pyserial


2. Pyfirmata


> pyserial is the base library for serial communication, it requires all the protocol designed by yourself (both the PC and the arduino sides), and of course it gives all the control of the project to you. the firmata protocol is a basic firmware for the arduino and similar boards to 'expose' the gpio trough the serial port to the PC host. it helps to implement the logic in higher levels (like javascript or in your case python with pyfirmata)  if you have something basic to do and need it quick use the firmata, if you want to learn from the arduino up to the python program use pyserial






