# Batttery-Management-System-Hardware-Design-STM32F072xx
In this project, I worked on controller unit of the battery management system and submodules such as RTC, LCD Display, SD-Card Reader, etc.

## Resources for Battery Management System
This is a book about BMS for future electric vehicles
- https://drive.google.com/file/d/1yqfjjxpPs_QqzFROTNTc2ZXgaryhGttu/view?usp=sharing

## Real-Time Clock Module Adafruit PCF8523 

This is a great battery-backed real time clock (RTC) that allows your microcontroller project to keep track of time even if it is reprogrammed, or if the power is lost. Perfect for datalogging, clock-building, time stamping, timers and alarms, etc. Equipped with PCF8523 RTC - it can run from 3.3V or 5V power & logic!
- PCB & header are included
- Plugs into any breadboard, or you can use wires
- Two mounting holes
- Will keep time for 5 years or more

## INA1x9 High-Side Measurement Current Shunt Monitor
The INA139 and INA169 are high-side, unipolar, current shunt monitors. Wide input common-mode voltage range, high-speed, low quiescent current, and tiny SOT-23 packaging enable use in a variety of applications.

I think I will use LM358 OPAMP for ampfying measured voltage, then deciding the direction of the current will be the task.
