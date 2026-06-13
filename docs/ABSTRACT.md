## Abstract

**Vital Nova Pod – Smart Infant Monitoring System** is an integrated embedded healthcare project designed to improve infant safety, comfort, and caregiver awareness through continuous real-time monitoring. The system uses ESP32-based modules to monitor vital health parameters such as heart rate, SpO₂, body temperature, motion, and stress indication using MAX30102, DS18B20, MPU6050, and GSR sensors.

The system also monitors environmental conditions around the infant using BME280 for temperature, humidity, and pressure, MQ135 for air quality, and a soil moisture sensor for diaper leakage detection. When abnormal conditions such as diaper wetness, unsafe air quality, high temperature, or critical health readings are detected, the system alerts caregivers through buzzer notifications and traffic-light status indicators.

To provide emotional comfort, the system includes a cry detection module using an LM393 sound sensor. When crying is detected, a DFPlayer Mini automatically plays a pre-recorded mother’s voice through a speaker. An ESP32-CAM module enables live video monitoring over Wi-Fi, allowing caregivers to visually observe the infant remotely within the same network. Emergency oxygen cylinder provision is also included as a safety concept for critical situations.

Overall, Vital Nova Pod combines health monitoring, environmental safety, diaper leakage detection, cry detection, mother voice response, live video surveillance, and emergency support into one smart infant care platform. This project aims to reduce parental anxiety, improve response time, and provide a safer monitoring solution for infants.
