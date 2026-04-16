# WiFi RC Car using ESP8266

## 📌 Overview

This project is a *WiFi-controlled RC car* powered by the ESP8266 microcontroller and controlled via the Blynk IoT mobile application. The system enables real-time wireless control of the car's movement including forward, backward, left, and right directions.

---

## 🎯 Objective

The main objective of this project is to design and implement a *wireless robotic system* using embedded systems and IoT technology.

Specifically, this project aims to:

* Develop a remotely controlled vehicle using WiFi communication
* Interface ESP8266 with L298N motor driver
* Control DC motors using digital signals and PWM
* Apply programming and circuit design concepts in a real-world system

---

## 🛠️ Components Used

* ESP8266 (NodeMCU)
* L298N Motor Driver
* 2 × DC Motors (N20)
* 18650 Lithium-ion Battery
* Robot chassis
* Jumper wires

---

## ⚙️ System Architecture

The system consists of three main parts:

### 1. Control Unit

* ESP8266 connects to WiFi and communicates with the Blynk Cloud
* Receives commands from the mobile application

### 2. Motor Driver

* L298N controls motor direction and speed
* Uses PWM for speed control

### 3. Power System

* 18650 battery supplies power to motors
* Common ground is shared across all components

---

## 🔌 Circuit Connections

| ESP8266 | L298N |
| ------- | ----- |
| D1      | IN1   |
| D2      | IN2   |
| D3      | IN3   |
| D4      | IN4   |
| D5      | ENA   |
| D6      | ENB   |

---

## 📱 Blynk Controls

| Control  | Virtual Pin |
| -------- | ----------- |
| Forward  | V0          |
| Backward | V1          |
| Left     | V2          |
| Right    | V3          |
| Speed    | V4 (Slider) |

---

## 💻 Features

* 📡 WiFi-based control
* 🎮 Real-time movement commands
* ⚡ Adjustable speed using PWM
* 🔄 Multi-directional control
* 📱 Mobile app interface

---

## 📊 Results

The system was successfully tested and achieved the following:

* Stable WiFi connection using ESP8266
* Smooth motor control via L298N
* Real-time response to user commands
* Adjustable speed control using slider input

---

## ⚠️ Limitations

* Dependent on WiFi connectivity
* Voltage drop in L298N reduces efficiency
* Battery must be monitored to prevent over-discharge

---

## 🚀 Future Improvements

* Add line follower using PID control
* Implement obstacle avoidance (ultrasonic sensor)
* Add manual/automatic mode switching
* Upgrade to more efficient motor driver (TB6612FNG)
* Add battery voltage monitoring system

---

## 📸 Project Preview

Add your images here (chassis, wiring, app UI)
