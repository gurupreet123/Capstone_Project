# 🔌 **IoT-Based Smart Energy Meter with Theft Detection & Remote Monitoring**

This project is a **smart energy meter system** developed using IoT technologies such as **ESP32, GSM modules, current/voltage sensors, and a mobile app interface (Blynk)**. It provides real-time energy consumption monitoring, remote load control, billing automation, and theft detection capabilities.

---

## 📌 **Features**

- 📲 **Real-time Monitoring** of voltage, current, and power using ESP32  
- 🧾 **Automated Billing** system based on live data  
- 🔐 **Theft Detection** logic to monitor tampering or unauthorized usage  
- ☁️ **Cloud Storage** of readings for historical analysis (via Firebase/Thingspeak)  
- 🔌 **Remote Load Control** through mobile app  
- 📉 **Energy Usage Graphs** and trend visualization  
- 📱 **Blynk Integration** for user-friendly mobile interface  

---

## ⚙️ **Technologies Used**

| **Component** | **Description** |
|--------------|-----------------|
| **ESP32**     | Microcontroller for processing and communication |
| **ZMPT101B**  | Voltage sensor |
| **SCT-013**   | Current sensor |
| **Blynk App** | Mobile app interface |
| **Firebase / Thingspeak** | Cloud storage and data visualization |
| **GSM Module (SIM800L)** | SMS alerts and communication (optional) |
| **Relay Module** | For remote load switching |

---

## 🛠️ **How It Works**

1. Sensors measure real-time voltage and current.  
2. ESP32 calculates power usage and pushes data to Firebase/Thingspeak.  
3. The Blynk app displays readings and allows control over connected appliances.  
4. Theft detection logic identifies anomalies and alerts the user.  
5. Monthly bills are generated automatically using consumption data.  

---

## 🧪 **Setup Instructions**

1. **Connect Components**
   - ESP32 + ZMPT101B + SCT-013 + Relay + GSM (optional)

2. **Upload Code**
   - Use Arduino IDE and upload `smart_meter.ino` to ESP32.

3. **Configure Firebase / Thingspeak**
   - Update credentials and API keys in the code.

4. **Set up Blynk**
   - Create a dashboard and link with your ESP32 auth token.

5. **Power the System**
   - Observe real-time data and use mobile app controls.

---


## 📚 **References**

- Patel, R., & Bhatt, D. (2018). *IoT Based Smart Energy Meter with Theft Detection Capability*  
- Agarwal, S., et al. (2019). *Smart Metering System Using GSM and Arduino for Energy Consumption Monitoring*  
- Hossain, M. M., et al. (2020). *IoT Enabled Smart Energy Meter with Remote Load Control and Monitoring*  
- Verma, N., & Agrawal, V. (2017). *Wireless Energy Meter Using IoT*  
- Sutar, R. S., et al. (2020). *An IoT Based Smart Energy Meter with Billing System*  
- Mulla, I., & Patil, D. (2018). *Smart Energy Meter using IoT for Advanced Metering Infrastructure*  
- Kumar, V., et al. (2019). *Design and Development of IoT Based Energy Monitoring System*  
- Nayak, D., & Sahoo, A. (2020). *Real Time Monitoring of Electricity Using IoT*  
- Kamble, A., & Kadam, D. (2021). *Smart Power Monitoring and Control System using IoT and Android Application*  
- Amin, R., et al. (2019). *Energy Meter Reading System Using IoT*  
- Rani, A., et al. (2020). *IoT Based Energy Meter Monitoring and Load Control*  
- Jadhav, P., & Kale, S. (2018). *IoT Based Energy Monitoring and Management System*  
- Rajput, S., & Singh, P. (2019). *A Review on Smart Metering Systems for Energy Monitoring and Management*  
- Deshmukh, P., et al. (2020). *Smart Energy Meter Using IoT*  
- **How2Electronics (2023).** *IoT Based Electricity Energy Meter Using ESP32 & Blynk.*  
---
