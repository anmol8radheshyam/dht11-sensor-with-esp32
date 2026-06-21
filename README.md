# ESP32 DHT22 Temperature Monitoring System

## Overview

This project demonstrates a simple IoT-based temperature and humidity monitoring system using an ESP32 microcontroller and a DHT22 sensor. The ESP32 continuously reads environmental data from the sensor and displays the temperature and humidity values on the Serial Monitor. The system also includes a threshold-based alert mechanism that notifies the user whenever the temperature exceeds a predefined limit.

This project is designed for beginners who want to learn sensor interfacing, embedded programming, and basic IoT concepts. It provides hands-on experience with real-time data acquisition and monitoring using ESP32.

---

## Features

* Real-time temperature monitoring
* Real-time humidity monitoring
* High-temperature alert system
* Serial Monitor output
* Simple and beginner-friendly implementation
* Compatible with Wokwi simulator and real ESP32 hardware

---

## Components Required

* ESP32 Development Board
* DHT22 Temperature and Humidity Sensor
* Jumper Wires
* Breadboard (optional)

---

## Circuit Connections

| DHT22 Pin | ESP32 Pin     |
| --------- | ------------- |
| VCC       | 3.3V          |
| DATA      | GPIO 4        |
| NC        | Not Connected |
| GND       | GND           |

---

## Working Principle

The DHT22 sensor measures both temperature and humidity from the surrounding environment. The ESP32 reads this data at regular intervals and prints the readings to the Serial Monitor. If the temperature rises above 30°C, the system generates an alert message indicating high temperature conditions.

This type of monitoring system can be used as a foundation for weather stations, smart homes, greenhouse monitoring, industrial monitoring, and other IoT applications.

---

## Software Used

* Arduino IDE
* ESP32 Board Package
* DHT Sensor Library
* Adafruit Unified Sensor Library
* Wokwi Simulator

---

## Sample Output

```text
Temperature: 28.4 °C
Humidity: 56.0 %

Temperature: 35.2 °C
Humidity: 60.5 %

ALERT! Temperature High
```

---

## Learning Outcomes

Through this project, you will learn:

* ESP32 programming basics
* Sensor interfacing techniques
* Reading digital sensor data
* Serial communication
* Threshold-based automation logic
* Fundamentals of Embedded Systems and IoT development

---

## Future Improvements

* Display data on an LCD/OLED screen
* Send alerts to a mobile application
* Integrate with Blynk or MQTT
* Store sensor data in the cloud
* Create a complete weather monitoring dashboard

This project serves as an excellent starting point for students and beginners interested in Embedded Systems, IoT, and smart automation technologies. 🚀
