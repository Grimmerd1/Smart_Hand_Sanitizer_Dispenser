# Smart_Hand_Sanitizer_Dispenser
## Overview

Smart Hand Sanitizer Dispenser is an IoT-based system designed to provide touchless hand sanitization and real-time monitoring. The system uses an ultrasonic sensor to detect hand presence and automatically dispenses sanitizer through a servo motor. Sensor data is transmitted via MQTT and visualized on a Node-RED dashboard.

## Features

* Automatic hand detection using an ultrasonic sensor
* Touchless sanitizer dispensing with a servo motor
* Real-time sanitizer level monitoring
* MQTT-based communication over Wi-Fi
* Node-RED dashboard for data visualization
* LED status indicators for sanitizer level alerts

## System Architecture

User → Ultrasonic Sensor → ESP32 → MQTT Broker → Node-RED Dashboard

## Technologies Used

* ESP32
* Embedded Linux
* MQTT
* Node-RED
* Ultrasonic Sensor
* Servo Motor
* Potentiometer
* LED Indicators

## System Logic

* Distance < 10 cm → Dispense sanitizer
* Sanitizer level ≥ 30% → Green LED
* Sanitizer level < 30% → Red LED warning

## Dashboard

The Node-RED dashboard displays:

* Sanitizer level gauge
* Distance gauge
* LED status indicator

![image alt](https://github.com/Grimmerd1/Smart_Hand_Sanitizer_Dispenser/blob/main/alcohol_level_1.png?raw=true)


## Results

The system successfully provides automatic sanitizer dispensing and real-time monitoring, reducing physical contact while improving hygiene and maintenance awareness.
