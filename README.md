# MEDITRACK--AI
Smart Hospital Equipment Management System – Hackathon Project

## 🚑 Project Overview

INNOV8 is a smart hospital equipment management system designed to improve the identification, monitoring, and management of medical equipment.

The system combines **IoT, RFID, sensors, ESP32, AI/ML, and a web-based platform** to provide smarter equipment monitoring and management.

## 🎯 Problem

Hospitals manage large numbers of medical equipment such as wheelchairs, patient beds, oxygen cylinders, first-aid kits, and blood-pressure monitors.

Manual tracking can make it difficult to know:

- Which equipment is being used
- Which equipment is available
- Whether equipment has been left unused
- The current status of equipment
- How equipment activity can be monitored efficiently

## 💡 Proposed Solution

Our system uses RFID-based equipment identification together with motion/activity sensing and an ESP32 controller.

The system can:

- Identify medical equipment using RFID
- Monitor equipment activity using sensors
- Detect equipment usage
- Provide local alerts using LEDs and a buzzer
- Send data through Wi-Fi
- Support integration with a web-based monitoring platform
- Provide a foundation for AI-powered equipment activity analysis

## ⚙️ System Architecture

RFID + Sensors
      ↓
    ESP32
      ↓
Sensor Data Processing
      ↓
AI / ML Analysis
      ↓
Equipment Status
      ↓
LED / Buzzer    
      ↓
Wi-Fi
      ↓
Web Platform / Dashboard

##🔧 Hardware
ESP32
RFID RC522
RFID Tags
PIR Motion Sensor
LED
Buzzer
Push Buttons
Breadboard
Jumper Wires

##💻 Technology Stack
Arduino IDE / C++
ESP32
RFID
PIR Sensor
Wi-Fi
Python
FastAPI
SQLite
HTML
CSS
JavaScript
AI/ML
Google Antigravity

##🤖 AI Integration
The project is designed to incorporate AI/ML for intelligent analysis of equipment activity and sensor data.
AI can be used to identify activity patterns, detect abnormal behavior, and support smarter equipment management.

##🌐 Communication
The ESP32 communicates through Wi-Fi and can exchange equipment information with the web platform using APIs and real-time communication.

##🚀 Future Scope
AI-based activity classification
Multi-sensor data fusion
Equipment location tracking
Hospital-wide equipment monitoring
Real-time dashboard
Predictive maintenance
Cloud-based data analytics
Integration with hospital management systems
