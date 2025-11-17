# IoT-Based-Smart-Compressor-Monitoring-and-Control-System

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="1100">
<br><br>

This project is an advanced IoT-powered system that enables real-time monitoring and intelligent control of air compressors.
It enhances operational reliability, minimizes unexpected downtime, and ensures optimal performance.
The system provides secure remote access to critical machine parameters anytime, anywhere

## ⭐ Features 🔑🔑

- **Real-time Monitoring:** : Tracks pressure, temperature, current, and vibration data continuously.

- **Remote Control:** Allows ON/OFF operation of the compressor from anywhere via IoT dashboard.

- **Smart Alerts:** Sends notifications for overload, overheating, abnormal vibration, or low pressure.

- **Cloud Data Logging:** Stores historical data on a cloud platform for analysis and performance trends.

- **Dashboard Visualization:** Shows live graphs, status indicators, and machine health insights.

- **Predictive Maintenance Ready:** Helps detect early faults to reduce breakdowns and maintenance cost.

- **Energy Efficiency Tracking:** Monitors power usage to optimize compressor running time.

- **Secure Communication:** Uses MQTT/HTTP with authentication for safe data transfer.

- **Scalable Design:** Can be adapted for multiple compressors or industrial setups.

- **Low-cost & Easy Integration:** Built using ESP32.



## 🛠️ Technologies Used

- **IoT Platform:** Blynk / Thingspeak / Firebase / MQTT Dashboard

- **Microcontroller:** ESP32 / NodeMCU (ESP8266)

- **Communication Protocol:** MQTT, HTTP/HTTPS

- **Sensors:** Pressure sensor, Temperature sensor, Current sensor, Vibration sensor

- **Cloud Services:** Real-time database & data visualization dashboards

- **Programming Language:** C/C++ (Arduino IDE / PlatformIO)

- **Database (Optional):** Firebase Realtime Database / MongoDB

- **Mobile App / Web UI:** Blynk App or custom IoT dashboard

- **Version Control:** Git & GitHub


## 🧩 System Architecture


- The system consists of an IoT-enabled microcontroller connected to sensors and a relay module, which collects compressor data and sends it to a cloud platform. Users can remotely monitor machine health and control the compressor through a dashboard or mobile app.



## 🏗️ Architecture Flow

- Sensors measure pressure, temperature, current, and vibration.

- Microcontroller (ESP32/NodeMCU) reads sensor data and processes it.

- Communication Protocol (MQTT/HTTP) sends data to the cloud.

- Cloud Platform stores data, generates alerts, and updates dashboards.

- User Interface (Mobile/Web App) displays real-time status and graphs.

- Control Commands from the app are sent back to the microcontroller.

- Relay Module switches the compressor ON/OFF based on commands or safety logic.



## 📦 Block Diagram Explanation


### 1. Sensors Unit

- Pressure Sensor → Monitors air pressure in the compressor.

- Temperature Sensor → Tracks motor and tank temperature.

- Current Sensor → Measures power consumption.

- Vibration Sensor → Detects abnormal vibrations indicating mechanical faults.

### 2. Microcontroller Unit

- ESP32 / NodeMCU collects sensor readings.

- Converts analog values into digital data.

- Processes threshold conditions and triggers alerts.

- Sends data to the cloud using Wi-Fi.

### 3. IoT Communication

- Uses MQTT or HTTP for lightweight, fast communication.

- Ensures reliable and secure data transfer.

### 4. Cloud / IoT Platform

- Receives and stores sensor data.

- Generates notifications for abnormal conditions.

- Visualizes data in real time using charts and gauges.

### 5. User Interface

- Displays live compressor status.

- Shows graphs for pressure, temperature, current, vibration, and uptime.

- Allows remote ON/OFF control of the compressor.

### 6. Control Unit

- A relay module controls the power supply to the compressor.

- Responds to user commands and safety triggers.

- Ensures protection from overload or overheating.



## 🛠️🔌 Hardware Used

- ESP32 / NodeMCU

- Pressure Sensor

- Temperature Sensor

- Vibration Sensor (optional)

- Current Sensor

- Relay Module

- Wi-Fi Module (built-in for ESP32)

## 🖥️ Software & Tools

- Arduino IDE / PlatformIO

- MQTT Broker / Thingspeak / Blynk / Firebase

- IoT Dashboard

- GitHub for version control


## 📚 Project Structure

├── /code
├── /circuit_diagram
├── /images
├── /documentation
└── README.md


## 🎯 Use Case

- Ideal for industries that want to reduce manual maintenance checks and enable smart predictive monitoring for compressors.



## 📄 License

- This project is licensed under the MIT License — you are free to use, modify, and distribute the code with proper attribution.
- Feel free to adapt it for academic, personal, or commercial use.

## 👥 Contributors

- Manjunath G L — Project Developer & Designer

- Your Name Here (Optional) — Hardware/Software Support

- Contributions and pull requests are welcome!
