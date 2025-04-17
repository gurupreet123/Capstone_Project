# IoT-Based Smart Energy Meter

An innovative IoT solution to monitor real-time electricity usage using ESP32 and ThingSpeak. This project helps users track voltage, current, power, and energy consumption (kWh) remotely from a web or mobile dashboard.

## 🔍 Problem Statement
Traditional energy meters do not provide real-time usage data. Manual readings can lead to billing errors, and users lack tools to monitor and control their energy consumption efficiently. There's a need for a low-cost, remote-accessible energy tracking system.

## 🎯 Objective
- Build a cost-effective energy meter using ESP32 and sensors.
- Calculate voltage, current, power, and energy in real-time.
- Upload data to the cloud (ThingSpeak) for visualization.
- Make energy data accessible anytime via mobile or web.
- Promote energy-saving habits through user awareness.

## 🛠️ Components Used
- ESP32 Wi-Fi Development Board  
- Voltage Sensor Module (AC transformer-based)  
- Current Sensor (CT Clamp)  
- LCD Display (Optional)  
- ThingSpeak Platform  
- Jumper Wires, Breadboard, Power Supply  

## 🧠 Working Principle
- Sensors measure AC voltage and current.
- ESP32 reads these signals and uses EmonLib to calculate:
  - Vrms (Voltage)
  - Irms (Current)
  - Apparent Power
  - Energy (kWh)
- Data is sent to ThingSpeak over Wi-Fi.
- Values are updated periodically and visualized in graphs.

## 🔄 Flowchart

1. Initialize system
2. Connect ESP32 to Wi-Fi
3. Read voltage and current
4. Compute power and energy
5. Upload data to ThingSpeak
6. Repeat after time interval

## 🌐 Cloud Interface - ThingSpeak
- Real-time graphs for Voltage, Current, Power, and Energy
- Accessible via web or mobile
- Historical data visualization and analytics
- Exportable datasets for further analysis

## 🌟 Features
- Real-time monitoring of electrical parameters
- Tracks total energy consumption (kWh)
- Live dashboard accessible from anywhere
- Open-source, affordable, and DIY-friendly
- Expandable with smart features

## 💡 Applications
- Home energy tracking
- Small offices and shops
- Educational/engineering projects
- Appliance-level usage analysis
- Smart grid/home automation integration

## 🚀 Future Scope
- Develop a mobile app for users to view individual energy meter readings.
- Add alarms, usage alerts, and energy recommendations.
- Voice assistant integration (Alexa/Siri) for quick queries.
- Energy cost estimation based on local tariffs.
- Smart control and load prediction using analytics.
## 📸 Hardware Setup
![image](https://github.com/user-attachments/assets/6906d562-403a-4293-9ca6-31e1f7ffdcbb)

## 📸 Sample Output
![image](https://github.com/user-attachments/assets/29da608d-006a-4f6b-bda3-0b8e961e2afd)
![image](https://github.com/user-attachments/assets/d4dd4e82-af5c-4b73-b340-c8a774f26a9f)

