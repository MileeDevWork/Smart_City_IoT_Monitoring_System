# Smart City IoT Monitoring System

An IoT-based smart city monitoring system for collecting, processing, and visualizing real-time environmental data using ESP32 and a ThingsBoard-based Core IoT platform.

## Overview

The system integrates multiple sensors with an ESP32 device to monitor environmental conditions and transmit real-time telemetry through MQTT. The data is visualized on an IoT dashboard, with configurable thresholds, alarms, and scheduled device control.

## Features

* 🌡️ Real-time temperature and humidity monitoring
* 🌫️ Air quality and motion monitoring
* 📡 MQTT communication over Wi-Fi
* 🔄 Automatic Wi-Fi reconnection
* ⚠️ Threshold-based environmental alarms
* ⏰ Scheduled parking light control

  * ON at 18:00
  * OFF at 06:00
* 🔄 OTA firmware update
* 📊 Real-time IoT dashboard and data visualization
* ⚙️ Device configuration using NVS

## Technologies

* **Embedded:** ESP32, FreeRTOS
* **Communication:** Wi-Fi, MQTT
* **IoT Platform:** ThingsBoard-based Core IoT Platform
* **Sensors:** DHT11, MQ135, PIR
* **Firmware:** NVS, OTA
* **Dashboard:** Core IoT / ThingsBoard-style Dashboard

## Dashboard

### Main Dashboard

![Main Dashboard](./img/mainpage.png)

### Environmental Monitoring

![Environmental Monitoring](./img/q1.png)

### Sensor Details & Alarms

![Sensor Dashboard](./img/benthanh.png)

### Parking Dashboard

![Parking Dashboard](./img/carpark.png)

## Demo

🎥 **Project Demo:** [Watch Demo](https://www.youtube.com/watch?v=kwJrfP_ZU7A)

