# Smart Home Security System with ESP32 and Blynk


<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/ae3e3c7d-ed44-45fc-9a85-f6fbf096fd0d
" alt="Project Overview" width="600" height="300">
</div>

## Introduction
This project implements a Smart Home Security System using the ESP32 microcontroller and the Blynk IoT platform. It integrates multiple sensors to monitor environmental conditions and control devices in response to detected anomalies. The system ensures real-time alerts and notifications through the Blynk mobile app.

## Features
- **Gas Leak Detection**: Detects gas leaks and triggers a pump to mitigate risks.
- **Water Level Monitoring**: Alerts users when the water level is too low.
- **Temperature Control**: Detects high temperatures and activates the pump for cooling.
- **Motion Detection**: Identifies motion and provides real-time alerts via the app.
- **Flame Detection**: Detects fire, activates a buzzer, and triggers safety measures.

## Technologies Used
- **ESP32 Microcontroller**
- **Blynk IoT Platform**
- **DHT22 Sensor** (Temperature and Humidity)
- **PIR Sensor** (Motion Detection)
- **Gas, Water, and Flame Sensors**
- **Wokwi Simulation Software**
- **Blynk Simple ESP32 Library**

## How It Works
1. **ESP32 Wi-Fi Connection**: The ESP32 connects to Wi-Fi using credentials provided in the code.
2. **Sensors Monitoring**: Sensors continuously monitor environmental parameters such as gas levels, temperature, water levels, motion, and flame presence.
3. **Blynk Integration**: The system communicates with the Blynk app to display real-time sensor data and trigger alerts in case of anomalies.
4. **Actuator Activation**: When an anomaly is detected (e.g., gas leak, high temperature, or flame), corresponding actuators like the pump or buzzer are activated.
5. **Real-time Notifications**: The system sends real-time alerts and notifications to the user through the Blynk app.

## Setup Instructions
1. **Clone the repository**: Clone this repository to your local machine.
2. **Install Libraries**: Install the necessary libraries, including Blynk and DHTesp, in your Wokwi project.
3. **Upload the Code**: Upload the code to your ESP32 using the Wokwi simulation platform.
4. **Connect the Sensors and Actuators**: Simulate the connections of sensors and actuators (DHT22, PIR, gas, water, and flame sensors) within Wokwi according to the pin configuration in the code.
5. **Configure the Blynk App**: 
   - Download and install the Blynk mobile app.
   - Create a new project in the Blynk app, selecting ESP32 as the device.
   - Obtain your **BLYNK_AUTH_TOKEN**.
6. **Update Credentials**: In the code, update the Wi-Fi credentials (`ssid`, `pass`) and **BLYNK_AUTH_TOKEN** obtained from the Blynk app.
7. **Run the System**: Start the simulation in Wokwi and monitor real-time data on the Blynk app.

## Code Explanation
1. **Wi-Fi and Blynk Setup**: The ESP32 connects to Wi-Fi and Blynk using the provided credentials.
2. **Sensor Readings**: The sensors continuously check for anomalies (e.g., gas leak, temperature, motion).
3. **Blynk Virtual Pins**: Sensor data and actuator statuses are sent to Blynk through virtual pins, allowing you to monitor and control devices remotely.
4. **Actuator Control**: Based on the sensor readings, the system activates actuators like the pump or buzzer.

## Conclusion
This Smart Home Security System provides real-time monitoring and control of home safety parameters, making use of ESP32 and Blynk. The system simulates sensor and actuator responses in Wokwi, providing a hands-on approach to creating an IoT-based security system.

