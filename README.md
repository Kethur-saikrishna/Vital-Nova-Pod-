Vital Nova Pod – Smart Infant Monitoring System

Overview

Vital Nova Pod is an intelligent infant healthcare and safety monitoring system designed to provide continuous supervision of a baby's physiological health, environmental conditions, emotional comfort, and visual safety. The system integrates multiple sensors, embedded controllers, smart alert mechanisms, and real-time monitoring technologies to assist parents and caregivers in ensuring infant well-being. 

The system continuously monitors:

* ❤️ Heart Rate
* 🩸 Blood Oxygen Saturation (SpO₂)
* 🌡 Body Temperature
* 🏃 Infant Movement and Motion
* 📈 Stress Indication
* 🌤 Environmental Temperature
* 💧 Humidity
* 🌫 Air Quality
* 🚼 Diaper Leakage Detection
* 😢 Baby Cry Detection
* 🎥 Live Video Monitoring

In addition, Vital Nova Pod provides automatic soothing through a pre-recorded mother's voice when infant crying is detected and includes an emergency oxygen support concept for enhanced neonatal safety. 


# 🎯 Problem Statement

Continuous infant monitoring is challenging for parents and caregivers. Babies cannot communicate discomfort, illness, breathing issues, temperature abnormalities, diaper wetness, or environmental discomfort effectively.

Traditional baby monitoring solutions generally provide only audio or video surveillance and often lack integrated physiological and environmental monitoring capabilities.

Vital Nova Pod addresses these limitations by combining:

* Health Monitoring
* Environmental Monitoring
* Cry Detection
* Intelligent Soothing Response
* Video Surveillance
* Emergency Safety Features

into a single smart platform. 


# 🚀 Key Features

### Baby Health Monitoring

* Heart Rate Monitoring using MAX30102
* SpO₂ Monitoring using MAX30102
* Body Temperature Monitoring using DS18B20
* Motion Monitoring using MPU6050
* Stress Detection using GSR Sensor

### Environmental Monitoring

* Temperature Monitoring using BME280
* Humidity Monitoring using BME280
* Air Quality Monitoring using MQ135
* Diaper Leakage Detection using Soil Moisture Sensor

### Cry Detection & Comfort System

* LM393 Sound Sensor detects infant crying
* DFPlayer Mini automatically plays recorded mother voice
* Speaker provides soothing audio response

### Live Video Monitoring

* ESP32-CAM real-time video streaming
* Remote infant observation through Wi-Fi network

### Safety Features

* Buzzer Alerts
* Traffic Light Health Indicator
* Cooling Fan Control
* Exhaust Fan Control
* Emergency Oxygen Cylinder Provision

### Smart Alert System

* High Temperature Alert
* Low Oxygen Alert
* Diaper Leakage Alert
* Poor Air Quality Alert
* Cry Detection Alert
* Critical Health Condition Alert

---

# 🛠 Hardware Components

| Component               | Function                         |
| ----------------------- | -------------------------------- |
| ESP32                   | Main Controller                  |
| ESP32-CAM               | Live Video Monitoring            |
| MAX30102                | Heart Rate & SpO₂                |
| DS18B20                 | Body Temperature                 |
| MPU6050                 | Motion Detection                 |
| GSR Sensor              | Stress Monitoring                |
| BME280                  | Temperature, Humidity & Pressure |
| MQ135                   | Air Quality Monitoring           |
| Soil Moisture Sensor    | Diaper Leakage Detection         |
| LM393 Sound Sensor      | Cry Detection                    |
| DFPlayer Mini           | Audio Playback                   |
| OLED Display            | Real-Time Display                |
| Buzzer                  | Alert Notification               |
| Traffic Light Indicator | Health Status Visualization      |
| Relay Module            | Fan Control                      |
| Exhaust Fan             | Air Circulation                  |
| Cooling Fan             | Temperature Control              |
| TP4056                  | Battery Charging                 |
| Lithium Battery         | Portable Power Supply            |

---

# 🧠 Working Principle

The system consists of four major modules:

### 1. Baby Health Monitoring Module

Measures:

* Heart Rate
* SpO₂
* Body Temperature
* Motion
* Stress Levels

Data is processed by ESP32 and displayed on OLED screens.

### 2. Environmental Monitoring Module

Measures:

* Temperature
* Humidity
* Air Quality
* Diaper Wetness

If unsafe conditions are detected:

* Buzzer activates
* Fans operate automatically

### 3. Cry Detection & Mother Voice Response

When baby crying is detected:

1. LM393 detects sound
2. DFPlayer Mini is triggered
3. Recorded mother voice is played
4. Baby receives emotional comfort

### 4. Live Video Monitoring

ESP32-CAM:

* Connects to Wi-Fi
* Creates live video stream
* Allows remote monitoring through browser

---

# 💡 Innovation Highlights

✅ Health Monitoring + Environmental Monitoring in one platform

✅ Smart Diaper Leakage Detection

✅ Mother Voice Comfort System

✅ Real-Time ESP32-CAM Monitoring

✅ Air Quality Monitoring

✅ Automated Environmental Control

✅ Emergency Oxygen Support Concept

✅ Portable Battery Powered Design

---

# 🔮 Future Scope

* Mobile Application Integration
* Cloud Data Storage
* AI-Based Cry Classification
* Health Prediction Algorithms
* Remote Hospital Connectivity
* SMS and Emergency Notifications
* AI-Powered Risk Analysis
* Smart Oxygen Automation
* Digital Health Records
* Neonatal ICU Integration

---

# 👨‍💻 Developed By

**Kethur Sai Krishna**
B.Tech – Electronics & Communication Engineering
AAR Mahaveer Engineering College, JNTUH
Embedded Systems & Product Development Enthusiast

---

# ❤️ Vision

**"To create an intelligent infant healthcare ecosystem that combines health monitoring, environmental safety, emotional comfort, and smart technology to improve infant well-being and reduce caregiver anxiety."**

 

