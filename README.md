# Alcohol-detection-iot-project
**INTRODUCTION**
In today's fast-paced world, ensuring road safety is paramount. One significant factor contributing to road accidents is driving under the influence of alcohol. To address this critical issue, we have developed an innovative Alcohol Detection System for Vehicle and Life Safety. This is an IoT-based project using an MQ3 sensor, Relay Module, NodeMCU and DC Motor with a propeller.
Our project focuses on integrating MQ3 into vehicles, providing real-time detection of alcohol presence in the driver's vicinity. When the sensor detects alcohol levels surpassing the safe limit, it triggers an automatic response by turning off the engine to ensure the safety of the driver,passengers, and others on the road.
**COMPONENTS**
NodeMCU,Breadboard,Jumperwires,MO3 sensor,Relay Module,Battery,DC Motor with Propeller
**CONNECTIONS**
**MQ3:**
A0 - A0 of NodeMCU
GND - GND
VCC - Vin
**Relay Module:**
IN - D1 of NodeMCU
VCC - Vin
GND - GND
NO - Motor Positive
COM - Battery Positive
**Battery:**
Positive - Relay COM
Negative - Motor Negative
**DC Motor with Propeller:**
Positive - Relay NO
Negative - Battery Negative
**WORKING**
The motor of the module is compared to the carengine. In normal cases when alcohol is not detected, them Motor isrunning likeacarengine. But when alcohol is detected, the motor will slowly turn off and will only turn on when no alcohol is detected. When the sensor is placed in the car, the engine will slowly turn off to prevent accidents
