# Requirements

## Introduction

This project is about Vehicle Tracking System. This system helps to track the vehicle location,vehicle speed, time and direction using GPS, GSM and Arduino. Vehicle information can be viewed on electronics maps via the internet. GPS Tracking system can potentially give both real-time and historic navigation data on any kind of journey.

## Research

### HISTORY OF VEHICLE TRACKING SYSTEM

![History of PMS](https://user-images.githubusercontent.com/59198753/142820003-0569fc32-2d4c-404e-a555-ce9a03c4ef6c.jpg)

## Cost Estimation

**Estimated cost = hours needed to build the entire automated system * cost per hour to build the automated system.

## Features

* GPS Receiver which gets location information from the satellites .
* ATmega328 Microcontroller process those data collected from the GPS receiver and send the information to the Mobile through GSM Module.
* SIM800A GSM Module is designed for wireless radiation monitoring through Short Messaging Service (SMS). This module is able to receive serial data from radiation monitoring devices such as survey meter or area monitor and transmit the data as text SMS to a host server.
* Vibration Sensor uses the piezoelectric effects while measuring the changes within acceleration, pressure, temperature, force otherwise strain by changing to an electrical charge.
* MQ7 Sensor makes detection by method of cycle high and low temperature, and detect CO when low temperature (heated by 1.5V). The sensor's conductivity is more higher along with the gas concentration rising. When high temperature (heated by 5.0V), it cleans the other gases adsorbed under low temperature.

## Features to be added in future

* deep-learning-based approach for image processing for vehicle detection and vehicle type classification.
* Computer vision technology to replace human eyes and complement GPS within yards, depots, and distribution centers.

## SWOT Analysis
![SWOT Analysis](https://user-images.githubusercontent.com/59198753/142820086-951e7b7b-8fb1-4132-b224-a5388751bb9f.jpg)

## 4 W's & 1 H
![4w 1h](https://user-images.githubusercontent.com/59198753/142821633-8a7b353d-2478-4df5-90fd-c60b5e75610a.jpg)

## Detail Requirements

### High Level Requirements
| ID    | Description                             | Status              | 
|-------|-----------------------------------------|---------------------|
| HLR01 | Vehicle speed detecting  |Implemented        |
| HLR01 | location of vehicle |Implemented         |
| HLR03 | Time and direction of the location in electronic maps  |Implemented             |


### Low Level Requirements
| ID    | Description           | Status              | 
|-------|-----------------------|---------------------|
| LLR01 |car and mobile interface integration          |   Implemented       |
| LLR02 |Connect to internet connection|   Implemented       |
| LLR03 |Connect to GPS         |Implemented           |
