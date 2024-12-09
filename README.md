# Smart Home Security System with ESP32 and Blynk

![Smart Home Image](https://allbetterapp.com/wp-content/uploads/2024/03/Smart-Home.jpg)


## Introduction
This project implements a **Smart Home Security System** using the ESP32 microcontroller and the Blynk IoT platform. It integrates multiple sensors to monitor environmental conditions and control devices in response to detected anomalies. The system ensures real-time alerts and notifications through the Blynk mobile app.

## Features
- **Gas Leak Detection**: Detects gas leaks and triggers a pump to mitigate risks.
- **Water Level Monitoring**: Alerts users when the water level is too low.
- **Temperature Control**: Detects high temperatures and activates the pump for cooling.
- **Motion Detection**: Identifies motion and provides real-time alerts via the app.
- **Flame Detection**: Detects fire, activates a buzzer, and triggers safety measures.

## Technologies Used
- ESP32 Microcontroller
- Blynk IoT Platform
- DHT22 Sensor (Temperature and Humidity)
- PIR Sensor (Motion Detection)
- Gas, Water, and Flame Sensors
- Arduino IDE for programming

## How It Works
1. ESP32 connects to Wi-Fi using credentials provided in the code.
2. Sensors continuously monitor environmental parameters.
3. The system communicates with the Blynk app to display sensor data and trigger alerts.
4. When an anomaly is detected, the system activates corresponding actuators like the pump or buzzer.
5. Real-time notifications are sent to the user via the Blynk app.

## Setup Instructions
1. Clone this repository to your local machine.
2. Install the necessary libraries: Blynk, DHTesp.
3. Upload the code to your ESP32 using the Arduino IDE.
4. Connect the sensors and actuators to the ESP32 as specified in the code.
5. Configure the Blynk app and obtain your `BLYNK_AUTH_TOKEN`.
6. Update the Wi-Fi and Blynk credentials in the code.
7. Run the system and monitor real-time data on the Blynk app.



