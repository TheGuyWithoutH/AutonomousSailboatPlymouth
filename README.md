# AutonomousSailboatPlymouth
The Ultrasonic files (Ultrasonic.cpp/Ultrasonic.h) is adapted from the code of https://github.com/Make-The-Light-Sing/HCSR04UltraSonic.

This is an Arduino code and it requires the following externals libraries (which you will find inside of the lib folder):
  - LiquidCrystal_I2C (https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library)
  - TinyGPS++ (https://github.com/mikalhart/TinyGPSPlus)
  - ds3231 (https://github.com/rodan/ds3231)

You need to move them to the Arduino Sketchbook folder (have a look to the preference menu to find it).

(I don't use anymore the libraries manager because it is not very efficient, knowing that some well designed libraries are not available on it, but some bad designed are... And you can just install and update libraries with it, but you can't delete one (you need to do it manually))

I chose to use a Makefile to generate the documentation and do some backup of the code, you will find it in the src/ folder.