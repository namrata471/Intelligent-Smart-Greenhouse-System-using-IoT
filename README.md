🌱 Intelligent Smart Greenhouse System using IoT

This project is an IoT-based smart greenhouse system developed to make greenhouse farming more efficient and easier to manage.

The system monitors important environmental conditions such as temperature, humidity, soil moisture, and light intensity in real time. Based on the collected data, it helps control devices such as the water pump and exhaust fan to maintain suitable conditions for plant growth.

The project also explores the use of Machine Learning and historical data to move from simple threshold-based control toward more data-driven monitoring and prediction.

 What This Project Does?

* Monitors temperature and humidity
* Measures soil moisture
* Monitors light conditions
* Controls irrigation using a water pump
* Provides ventilation using DC fans
* Uses ESP32 as the main microcontroller
* Sends/handles data using cloud platforms
* Uses Python and Machine Learning for analysis
* Supports historical data and prediction
* Aims to enable remote monitoring and control

🛠️ Technologies Used

 Hardware

* ESP32 Microcontroller
* DHT11/DHT22 Temperature & Humidity Sensor
* Capacitive Soil Moisture Sensor
* Display Module
* 12V Water Pump
* DC Exhaust Fans
* Relay Motor Driver
* DC Power Supply

Software

* Arduino IDE
* Python
* Machine Learning
* Firebase / ThingSpeak

 ⚙️ How It Works

The sensors collect environmental information from the greenhouse and send the readings to the ESP32.

The collected data can then be stored and monitored through a cloud platform. The data is used for analysis and Machine Learning-based decision making.

Based on the conditions inside the greenhouse, devices such as the water pump and exhaust fan can be controlled automatically.

```text
Sensors
   ↓
ESP32
   ↓
Data Collection
   ↓
Cloud / Data Storage
   ↓
Data Analysis & Machine Learning
   ↓
Decision Making
   ↓
Pump / Fan / Lighting Control
```

 🤖 Machine Learning (Implementing)

One of the main improvements in this project is the use of Machine Learning.

Instead of depending only on fixed threshold values, the system is designed to use historical and real-time data for analysis and prediction.

Machine Learning is mainly considered for:

* Predictive irrigation
* Condition monitoring
* Data analysis
* Decision making
* Historical data-based prediction

🌿 Applications

This system can be useful for:

* Greenhouses and polyhouses
* High-value crop cultivation
* Exotic vegetables
* Flowers and medicinal plants
* Nurseries
* Plant research centers
* Precision agriculture
* Commercial smart farming

 ✅ Advantages

* Helps improve crop growing conditions
* Reduces unnecessary water usage
* Reduces manual monitoring
* Supports automated control
* Provides real-time environmental information
* Enables data-based decision making
* Supports remote monitoring

🔮 Future Scope

The project can be further improved by adding:

* More environmental sensors
* Better Machine Learning models
* More historical data for prediction
* A complete web/mobile dashboard
* Advanced energy monitoring
* Improved irrigation prediction
* Fault detection and alerts
* Solar-powered operation

 🌍 Sustainable Development Goals

This project is related to:

SDG 2 – Zero Hunger

By supporting better crop conditions and precision agriculture.

SDG 12 – Responsible Consumption and Production

By focusing on efficient use of water and other agricultural resources.


🌱 Project Goal

The main goal is to make greenhouse farming more automated, data-driven, resource-efficient, and easier to monitor using IoT and Machine Learning.
