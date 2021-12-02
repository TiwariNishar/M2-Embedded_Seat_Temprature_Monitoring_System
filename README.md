# M2-Embedded_Seat_Temprature_Monitoring_System

## Introduction
![image](https://user-images.githubusercontent.com/94336423/144357272-579bac57-9fed-40dd-8d20-fc2865c2a7f4.png)

## Activity 1

To turn on led when the passenger is sitting on the seat and the heater is on.
 
 
## Activity 2

To read the values given to the ADC from the temperature sensor.


## Activity 3

To generate PWM pulses according to the ADC values and displaying it on a CRO.


|ADC value|	Output PWM(Duty Cycle)|	Temperature|
|---------|-----------------------|------------|
|0-200|	20%|	20°C|
|210-500|	40%|	25°C|
|510-700|	70%|	29°C|
|710-1024|	90%|	33°C|


## Folder Structure

|Folder|	Description|
|------|-------------|
|1_Requirements|	Documents detailing requirements and research|
|2_Design|	Documents specifying design details|
|3_Implementation|	All code and documentation|
|4_Implementation|	Documents with Implementation and procedures|
|5_TestPlan|Diffrent Test cases and there Outputs| 

[![Compile-Linux](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Compile.yml/badge.svg)](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Compile.yml)
[![Cppcheck](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Codequality.yml/badge.svg)](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Codequality.yml)
[![C/C++ CI](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/c-build.yml/badge.svg)](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/c-build.yml)
[![Valgrind](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/actions/workflows/Valgrind.yml)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/ced8fba95ab24a539a975694650b83f1)](https://www.codacy.com/gh/TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=TiwariNishar/M2-Embedded_Seat_Temprature_Monitoring_System&amp;utm_campaign=Badge_Grade)
[![Code Quality Score](https://api.codiga.io/project/30207/score/svg)
[![Code Badge](https://api.codiga.io/project/30207/status/svg)
