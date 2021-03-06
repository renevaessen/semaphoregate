# SemaphoreGate
Arduino firmware for a simple device that keeps track and controls number of people inside a room/building

## Description
This firmware can be used to build  a small device that is capable of counting visitors and limiting access
to a particular room or building, using two infrared sensors, a traffic light (red, green),
and a buzzer at the entrance.

The idea here is that such a device might help business owners to setup a more covid-19 safe environment where
visitors can be sure to have enough space inside, to keep appropiate distances from each other.

## Control
The LCD panel will show the two parameters (current, and maximum).

For changing the two parameters (current, and maximum) there are three buttons.

Namely, "R", "+" and "-"

Holding "R" for 5 seconds resets device to default settings

Pressing "-" or "+" changes the "maximum" parameter.

Holding "R" and then pressing "-" or "+" changes the "current" parameter.

## Hardware

   - Arduino Uno
   - HD44780 1602 LCD Module Display with I2C interface 2x16 characters