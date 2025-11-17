# 📡IoT-Based-Smart-Compressor-Monitoring-and-Control-System📡
<img width="1258" height="775" alt="image" src="https://github.com/user-attachments/assets/337509f2-7b68-4510-9745-17282bcbb6d3" />

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="1100">
<br>

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
<img width="1111" height="923" alt="image" src="https://github.com/user-attachments/assets/284a6ac3-8f91-4ffd-9415-d4e194647730" />




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
<img width="1161" height="852" alt="image" src="https://github.com/user-attachments/assets/3de7f20a-a23c-4d40-a2bd-ea395de43e59" />



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
<img width="1064" height="660" alt="image" src="https://github.com/user-attachments/assets/46cef573-b17f-46b8-a762-692b133ffdc9" />


- A relay module controls the power supply to the compressor.

- Responds to user commands and safety triggers.

- Ensures protection from overload or overheating.
  

## 📐 Schematic Diagram

  

  <img width="1100" height="678" alt="image" src="https://github.com/user-attachments/assets/efd7ded1-268e-4f67-806e-6c42f5b60f79" />




## 🛠️🔌 Hardware Used

- ESP32 / NodeMCU

- Pressure Sensor

- Temperature Sensor

- Vibration Sensor (optional)

- Current Sensor

- Relay Module

- Wi-Fi Module (built-in for ESP32)
  <p align="center">

<div style="display: flex; justify-content: space-between; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/f2500718-b880-482d-b52a-0c66acdabb79" width="32%" />
  <img src="https://github.com/user-attachments/assets/947e24b1-4fed-4c1c-9ed6-1cbf167f80df" width="32%" />
  <img src="https://github.com/user-attachments/assets/6f86176a-49b0-467e-97bf-530c7bf065ae" width="32%" />
</div>

</p>

 
  
  



## 🖥️ Software & Tools

- Arduino IDE / PlatformIO

- MQTT Broker / Thingspeak / Blynk / Firebase

- IoT Dashboard

- GitHub for version control

  
 
<p align="center">
  <img src="https://github.com/user-attachments/assets/a7f051c4-5d05-4195-9f49-16985fd7302c" width="32%" />
  <img src="https://github.com/user-attachments/assets/a4228076-df6c-47c7-a304-ccb11215d74c" width="32%" />
  <img src="https://github.com/user-attachments/assets/39af0e90-2dfc-4b92-b67c-836f68e8bc82" width="32%" />
  <br/>
  <img src="https://github.com/user-attachments/assets/d6a1909f-f731-4629-a5c8-06122ecc5169" width="32%" />
  <img src="https://github.com/user-attachments/assets/a411464b-3e92-4400-810c-376646a9be35" width="32%" />
</p>







  


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
