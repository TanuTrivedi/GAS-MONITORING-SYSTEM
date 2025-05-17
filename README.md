# GAS-MONITORING-SYSTEM
# 🛑 Gas Monitoring System using IoT

A real-time gas detection and alert system that uses IoT technology to monitor harmful gas levels in the environment and send alerts when unsafe levels are detected. This project focuses on safety, especially in industrial, kitchen, or laboratory settings.

##  Project Overview

This IoT-based system continuously monitors the air for dangerous gases such as LPG, methane, or carbon monoxide. If gas levels exceed a defined threshold, the system triggers an alert through buzzer and optional cloud notification, ensuring quick response and safety.

##  Components Used

- **MQ-2 / MQ-135 Gas Sensor** – detects harmful gases  
- **ESP32 / Arduino UNO** – microcontroller to process sensor data  
- **Buzzer / LED** – for local alert  
- **LCD Display**  – to show gas concentration in real-time  
- **Wi-Fi Module / ESP32** – to send alerts to IoT dashboard  
- **IoT Platform (ThingSpeak / Blynk / ) – for online alerts and monitoring

## Technologies Used

- Embedded C / Arduino IDE  
- IoT Cloud Platforms: ThingSpeak, Blynk, IFTTT (for alerts)  
- Sensors and Actuators: MQ Series, Buzzer  
- Real-time data logging and visualization

## How It Works

1. **Gas sensor** continuously reads gas concentration in the environment  
2. If gas level exceeds safe threshold, the system:  
   - Activates **buzzer/LED** for local alert  
   - Sends data to **IoT cloud** for remote monitoring  
   - Triggers LIKE alerts /buzzers 
3. User can monitor live data via **mobile app or web dashboard**


##  Features

- Real-time gas level monitoring  
- Local and remote alerts  
- IoT dashboard for data visualization  
- Energy efficient and reliable  
- Easy to install and maintain


##  Future Enhancements

- Add temperature and humidity monitoring  
- Use AI/ML to predict gas leaks based on patterns  
- Mobile app with real-time alert system  
- Integration with automatic exhaust fan


