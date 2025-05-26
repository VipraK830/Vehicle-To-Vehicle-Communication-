Vehicle-To-Vehicle-Communication
Developed a Vehicle-to-Vehicle (V2V) communication system using the CAN protocol to share speed, obstacle, alcohol, and accident data in real time. Integrated Blynk app via Wi-Fi for remote alerts, enhancing road safety through real-time monitoring and notifications.

This project implements a real-time Vehicle-to-Vehicle (V2V) communication system using the Controller Area Network (CAN) protocol, enhanced with IoT (ESP32), cloud notifications via Blynk, and accident prediction. The system enables vehicles to share crucial data like speed, alcohol detection, drowsiness, obstacle detection, and accidents, promoting proactive road safety.

## Features
- Accident Prediction, using AI and sensor fusion
- Alcohol Detection, with MQ35 sensor and auto lock
- Drowsiness Detection, using eye blink sensor
- Vehicle Proximity Alerts, via ultrasonic sensors
- Speed Control, based on sensor data
- CAN FD Protocol, for real-time V2V communication
- Wi-Fi Module (ESP32),for cloud integration
- Blynk App Notifications, for real-time remote alerts
- In-vehicle alerts via LEDs, Buzzer, LCD

 ## Hardware Components/Data Sources
- Arduino Uno / NodeMCU (ESP32)
- CAN Module
- MQ35 Alcohol Sensor
- Eye Blink Sensor (IR-based)
- Ultrasonic Sensors
- MPU6050 (for motion/rash driving detection)
- LCD Display (I2C), LEDs, Buzzer
- L298 Motor Driver, DC Motor
- Accident Sensor
- RFID module
  
 ## Software & Tools
- Arduino IDE
- Embedded C
- Blynk IoT App (Mobile)
- Cloud dashboard (via Blynk)
  
 ## System Architecture
![Architecture diagram](https://github.com/user-attachments/assets/d792d5f4-3edc-4639-ae0c-d1c3d9307089)

This architecture integrates multiple sensors and modules with a microcontroller for real-time data collection, analysis, and alerts. Data is exchanged via the CAN protocol and sent to the Blynk app via Wi-Fi for remote monitoring. Drowsiness, alcohol, and accidents trigger both in-vehicle and cloud-based alerts.

 ## Conclusion

This project offers a scalable and intelligent transportation solution by combining CAN protocol, sensor networks, and IoT to facilitate safe and efficient vehicle-to-vehicle communication. Real-time alerts through the Blynk app ensure quick responses to hazards, supporting a smarter and safer road ecosystem.

