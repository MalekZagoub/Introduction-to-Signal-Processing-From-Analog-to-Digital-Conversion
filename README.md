<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Home Security System with ESP32 and Blynk</title>
</head>
<body>
    <h1>Smart Home Security System with ESP32 and Blynk</h1>
    
    <h2>Introduction</h2>
    <p>
        This project implements a <strong>Smart Home Security System</strong> using the ESP32 microcontroller and the Blynk IoT platform. It integrates multiple sensors to monitor environmental conditions and control devices in response to detected anomalies. The system ensures real-time alerts and notifications through the Blynk mobile app.
    </p>
    
    <h2>Features</h2>
    <ul>
        <li><strong>Gas Leak Detection</strong>: Detects gas leaks and triggers a pump to mitigate risks.</li>
        <li><strong>Water Level Monitoring</strong>: Alerts users when the water level is too low.</li>
        <li><strong>Temperature Control</strong>: Detects high temperatures and activates the pump for cooling.</li>
        <li><strong>Motion Detection</strong>: Identifies motion and provides real-time alerts via the app.</li>
        <li><strong>Flame Detection</strong>: Detects fire, activates a buzzer, and triggers safety measures.</li>
    </ul>
    
    <h2>Technologies Used</h2>
    <ul>
        <li>ESP32 Microcontroller</li>
        <li>Blynk IoT Platform</li>
        <li>DHT22 Sensor (Temperature and Humidity)</li>
        <li>PIR Sensor (Motion Detection)</li>
        <li>Gas, Water, and Flame Sensors</li>
        <li>Arduino IDE for programming</li>
    </ul>
    
    <h2>How It Works</h2>
    <ol>
        <li>ESP32 connects to Wi-Fi using credentials provided in the code.</li>
        <li>Sensors continuously monitor environmental parameters.</li>
        <li>The system communicates with the Blynk app to display sensor data and trigger alerts.</li>
        <li>When an anomaly is detected, the system activates corresponding actuators like the pump or buzzer.</li>
        <li>Real-time notifications are sent to the user via the Blynk app.</li>
    </ol>
    
    <h2>Setup Instructions</h2>
    <ol>
        <li>Clone this repository to your local machine.</li>
        <li>Install the necessary libraries: Blynk, DHTesp.</li>
        <li>Upload the code to your ESP32 using the Arduino IDE.</li>
        <li>Connect the sensors and actuators to the ESP32 as specified in the code.</li>
        <li>Configure the Blynk app and obtain your <code>BLYNK_AUTH_TOKEN</code>.</li>
        <li>Update the Wi-Fi and Blynk credentials in the code.</li>
        <li>Run the system and monitor real-time data on the Blynk app.</li>
    </ol>
    
    <h2>Project Structure</h2>
    <ul>
        <li><code>main.ino</code>: The primary Arduino code for the project.</li>
        <li><code>README.md</code>: This documentation file.</li>
        <li><code>Images/</code>: Contains images of the system setup and app interface.</li>
    </ul>
    
    <h2>Contributing</h2>
    <p>
        Contributions are welcome! Please feel free to fork this repository and submit pull requests with your improvements.
    </p>
    
    <h2>License</h2>
    <p>
        This project is licensed under the <strong>MIT License</strong>. See the <code>LICENSE</code> file for details.
    </p>
</body>
</html>
