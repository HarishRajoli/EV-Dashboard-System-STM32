# 🚗 EV Dashboard System using STM32 Blue Pill

## 📌 Project Overview

The **EV Dashboard System** is an Embedded Systems Internship project that simulates the dashboard of an Electric Vehicle (EV). The system is developed using the **STM32 Blue Pill (STM32F103C8T6)** microcontroller and communicates with a **Python Dashboard** through UART. The project is simulated using **PICSimLab** and includes basic **ADAS (Advanced Driver Assistance System)** features such as obstacle detection and collision warning.

---

## 🎯 Objectives

- Simulate Electric Vehicle (EV) behaviour
- Monitor vehicle speed
- Estimate Battery State of Charge (SOC)
- Calculate driving range
- Monitor motor temperature
- Detect nearby obstacles using Ultrasonic Sensor
- Display real-time data on a Python Dashboard
- Implement basic ADAS safety features

---

## ✨ Features

- 🚗 Real-time EV Dashboard
- ⚡ Battery SOC Monitoring
- 📍 Driving Range Estimation
- 🌡️ Motor Temperature Monitoring
- 🚨 Front Collision Warning
- ↔️ Left & Right Obstacle Detection
- 📡 UART Communication
- 💻 Python GUI Dashboard
- 🧪 PICSimLab Simulation

---

## 🛠 Hardware Used

- STM32F103C8T6 Blue Pill
- HC-SR04 Ultrasonic Sensor
- LEDs
- Buzzer
- Potentiometers
- USB to UART Converter

---

## 💻 Software Used

- STM32CubeIDE
- PICSimLab
- Python
- VSPE (Virtual Serial Port Emulator)

---

## 📂 Project Structure

```text
EV-Dashboard-System-STM32
│
├── Documentation
│   └── Internship Presentation
│
├── Images
│   └── Project Screenshots
│
├── Python_Dashboard
│   └── Python Dashboard Source Code
│
├── STM32_Code
│   ├── Core
│   ├── Drivers
│   ├── .ioc
│   ├── .project
│   └── Source Files
│
└── README.md
```

---

## 🔄 Project Workflow

1. Read sensor data using STM32 Blue Pill.
2. Process EV parameters.
3. Send data through UART.
4. Python Dashboard receives the data.
5. Dashboard displays Speed, Battery, Range, Temperature, and ADAS alerts.

---

## 📷 Project Screenshots

Screenshots are available in the **Images** folder.

---

## 🚀 Future Improvements

- GPS Integration
- IoT Cloud Monitoring
- Mobile Application
- Battery Health Prediction
- Voice Alerts
- AI-based Driver Assistance

---

## 👨‍💻 Author

**Harish Rajoli**

Electronics and Communication Engineering (ECE)

GitHub: https://github.com/HarishRajoli

---

## 📜 License

This project is created for learning and educational purposes during my Embedded Systems Internship.
