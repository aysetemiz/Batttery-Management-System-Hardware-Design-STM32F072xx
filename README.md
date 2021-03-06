# Batttery-Management-System-Hardware-Design-STM32F072xx
In this project, I worked on controller unit of the battery management system and submodules such as RTC, LCD Display, SD-Card Reader, etc.

## Resources for Battery Management System

Battery Management Algorithms for Electric Vehicles Book
- https://drive.google.com/file/d/1yqfjjxpPs_QqzFROTNTc2ZXgaryhGttu/view?usp=sharing
- https://drive.google.com/file/d/1W2pc-Aq8FA_OLn01mX5mCkymhOy-EDvs/view?usp=sharing

TI Switching Fundamentals Booklet
- https://drive.google.com/file/d/1EPegQXz08HtQZqb1oqOuBoQKlCQRaX37/view?usp=sharing

Current Sensing with Different Types of Amplifiers
- https://drive.google.com/file/d/1_F7Duc_1Qy7WURkofty_rwruYl8Tk54K/view?usp=sharing
## Electronic Components

### AD5247 Digital Potentiometer
The AD5247 provides a compact, 2 mm × 2.1 mm, packaged solution for 128-position adjustment applications. This device
performs the same electronic adjustment function as a mechanical potentiometer or a variable resistor.

Link: https://www.analog.com/en/products/ad5247.html
### Real-Time Clock Module Adafruit PCF8523 

This is a great battery-backed real time clock (RTC) that allows your microcontroller project to keep track of time even if it is reprogrammed, or if the power is lost. Perfect for datalogging, clock-building, time stamping, timers and alarms, etc. Equipped with PCF8523 RTC - it can run from 3.3V or 5V power & logic!
- PCB & header are included
- Plugs into any breadboard, or you can use wires
- Two mounting holes
- Will keep time for 5 years or more
Link: https://www.nxp.com/docs/en/data-sheet/PCF8523.pdf

### INA1x9 High-Side Measurement Current Shunt Monitor
The INA139 and INA169 are high-side, unipolar, current shunt monitors. Wide input common-mode voltage range, high-speed, low quiescent current, and tiny SOT-23 packaging enable use in a variety of applications.

I think I will use LM358 OPAMP for ampfying measured voltage, then deciding the direction of the current will be the task. 

### LM358A Differential Amplifier for Shunt Current Measurement  

**LM358A**

Supply Voltage: 3-30V

Offset voltage+-3, +-7

Input bias current 20/250, 15/100

Gain bandwidth 700 kHz

Supply current 35mA

Slew rate: 0.3 V/us

Operating ambient temp: 0-70 degree celcius

**Slew rate** is defined as the maximum rate of change of an op amps output voltage, and is given in units of volts per microsecond

