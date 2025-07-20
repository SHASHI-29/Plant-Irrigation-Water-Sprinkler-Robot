# 🌿 Plant Irrigation & Water Sprinkler Robot 🤖💧

A smart agriculture robot built using Arduino to automate irrigation and optimize water usage. The system integrates soil moisture sensors, ultrasonic sensors, IR proximity, and a water pump to intelligently control irrigation in real-time.

---

## 🔧 Built With

- **Arduino Uno / Mega**
- **Embedded C**
- **Soil Moisture Sensor**
- **Ultrasonic Sensor**
- **IR Proximity Sensor**
- **Water Pump + Relay**
- **RemoteXY App Interface**
- **Servo Motors**
- **AFMotor Library**

---

## 📝 Project Description

This project automates irrigation in agricultural fields by detecting soil moisture levels and activating a water pump-controlled sprinkler when needed. Designed to conserve water and minimize manual labor, it provides real-time feedback via sensors and a mobile app (RemoteXY). It's suitable for both small gardens and scalable for large farms.

---

## ✅ Key Features

- 🌱 **Automated Soil Monitoring**  
  Triggers irrigation when moisture falls below threshold.

- 🚿 **Smart Sprinkler Activation**  
  Controls water pump for optimal hydration.

- ⚙️ **Real-Time Monitoring**  
  Soil moisture and water level status on app display.

- 📉 **Water Conservation**  
  Stops watering once moisture is sufficient.

- 🔋 **Energy Efficient**  
  Uses low power components, suitable for remote areas.

- 🧠 **Arduino-Based Logic**  
  Embedded logic ensures fast, local decision making.

- 🌍 **Scalable & Eco-Friendly**  
  Easily extended for multi-zone irrigation and sustainable farming.

---

## 📂 Example Use Case

A farmer deploys the robot in a paddy field. It continuously monitors the soil moisture. When the soil becomes dry (e.g., moisture < 20%), the system automatically activates the sprinkler. Once moisture level reaches safe limits (> 60%), irrigation is turned off — saving water and time.

---

## 🔮 Future Enhancements

- 🌐 **IoT Integration**: Add Wi-Fi/GSM for remote monitoring and alerts.
- ☁️ **Cloud Dashboard**: Visualize real-time sensor data using Blynk or ThingSpeak.
- ☀️ **Solar Power**: Operate using renewable energy.
- 🌧️ **Rain Sensor**: Avoid unnecessary watering during rain.
- 🧩 **Zone Control**: Independently manage different farm zones.

---

## 🖥️ Code Overview

The code utilizes:
- Soil moisture readings to control irrigation logic.
- Ultrasonic sensor to monitor water tank levels.
- IR proximity sensor for obstacle detection.
- RemoteXY interface for user control and status monitoring.
- Servo control for positioning sprinklers.

---

## 📸 Demo Screenshots / Hardware 
<p float="left">
  <img src="https://github.com/SHASHI-29/Plant-Irrigation-Water-Sprinkler-Robot/blob/main/images/output1.jpg" width="300"/>
  <img src="https://github.com/SHASHI-29/Plant-Irrigation-Water-Sprinkler-Robot/blob/main/images/output2.jpg" width="300"/>
</p>


---

## ▶️ Getting Started

### 📌 Prerequisites
- Arduino IDE
- RemoteXY App on Android/iOS
- AFMotor and Servo libraries
- Hardware: Arduino, sensors, motor driver (L293D), water pump, etc.

### 🔌 Wiring & Circuit
Refer to the `/circuit_diagram` directory or images in the repo.
1. Connect your Arduino board.
2. Install required libraries in Arduino IDE.
3. Upload the code from `main.ino`.

---

## 📲 RemoteXY App Setup

Use the RemoteXY configurator to build the UI using the provided configuration array. Connect via USB or Bluetooth as per your hardware.

