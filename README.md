# 🐄 IoT Livestock Monitoring System

## 📖 Overview
This project monitors livestock health and location using **IoT sensors + GPS**.  
It helps farmers track animals in real-time and get **health alerts** (fever, abnormal heart rate) or **location alerts** (animal lost).

---

## ⚙️ Features
- GPS tracking of livestock  
- Body temperature monitoring  
- Heart rate monitoring  
- MQTT-based data transfer to the cloud  
- Raspberry Pi gateway with CSV logging  
- Real-time alerts for abnormal health or lost animals  

-----

## 🛠 Hardware
- **ESP32** (MicroPython)  
- **GPS module** (e.g., NEO-6M)  
- **MAX30100 / MAX30102** (heart rate sensor)  
- **Temperature sensor** (DS18B20 or DHT11)  
- **Raspberry Pi**  

---

## 🧑‍💻 Software
- MicroPython on ESP32  
- Python 3 on Raspberry Pi  
- Dependencies:
```bash
pip install paho-mqtt
