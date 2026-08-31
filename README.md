# 🤖 IoT-Based Smart Desk Assistant Bot using ESP32-C3



<p align="center">

![ESP32-C3](https://img.shields.io/badge/ESP32--C3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Blynk](https://img.shields.io/badge/Blynk-23C48E?style=for-the-badge)
![IoT](https://img.shields.io/badge/IoT-00599C?style=for-the-badge)
![Embedded C](https://img.shields.io/badge/Embedded_C-2E8B57?style=for-the-badge)
![OLED](https://img.shields.io/badge/OLED_Display-000000?style=for-the-badge)

</p>

---

## 📌 Overview

The IoT-Based Smart Desk Assistant Bot is an ESP32-C3 powered desktop assistant designed to provide useful information and reminders directly on an OLED display.

The system connects to Wi-Fi, synchronizes time using NTP, fetches weather information, displays reminders, and can be remotely controlled using the Blynk IoT platform.

This project demonstrates Embedded Systems, IoT communication, cloud connectivity, and real-time user interface design.

---

## ✨ Features

- 🌦 Real-time Weather Updates
- 🕒 NTP-Synchronized Digital Clock
- 🔔 Reminder Alerts
- 📺 OLED Display Interface
- 📱 Remote Control using Blynk IoT
- 📡 Wi-Fi Connectivity
- ⚡ Low-Power ESP32-C3 Implementation

---

## 🛠 Hardware Components

| Component | Purpose |
|-----------|----------|
| ESP32-C3 Mini | Main Controller |
| OLED Display | User Interface |
| Buzzer | Reminder Alerts |
| Push Buttons | User Input |
| USB Power | Power Supply |

---

## 🧠 Software Stack

- Embedded C
- Arduino IDE
- Blynk IoT
- NTP Client
- Weather API
- Wi-Fi Library

---

## 🏗 System Architecture

<p align="center">
  <img src="Images/System_Architecture.png" width="85%">
</p>

Data Flow:

1. ESP32 connects to Wi-Fi.
2. NTP server provides current time.
3. Weather API provides live weather.
4. Blynk sends remote commands.
5. OLED displays information.
6. Buzzer triggers reminder alerts.

---

## 📸 Project Gallery

### Hardware Prototype

![Hardware](Images/Hardware.jpg)

### OLED Display

![OLED](Images/OLED_Display.jpg)

### Blynk Dashboard

![Dashboard](Images/Dashboard.png)

---

## 🚀 Getting Started

### Requirements

- ESP32-C3 Board
- Arduino IDE
- Blynk Account
- Wi-Fi Network

### Installation

1. Clone this repository.

```bash
git clone https://github.com/Atharva1305/iot-desk-assistant-bot-esp32.git
```

2. Open the project in Arduino IDE.
3. Install required libraries.
4. Add Wi-Fi credentials.
5. Add Blynk Auth Token.
6. Upload to ESP32-C3.

---

## 📂 Repository Structure

```
Firmware/
Hardware/
Images/
Documentation/
Videos/
```

---

## 🔮 Future Improvements

- Voice Assistant Integration
- AI-based Personal Assistant
- Google Calendar Synchronization
- MQTT Support
- Touch Display Interface
- Battery Backup

---

## 📚 Publication

The research work based on this project was presented at an IEEE Conference.

> Design and Implementation of an IoT-Based Desk Assistant Bot Using ESP32

---

## 👨‍💻 Author

**Atharva R. Bhagwat**

Embedded Systems Engineer

- LinkedIn: linkedin.com/in/atharvabhagwat13
- GitHub: github.com/Atharva1305
- Email: atharvabhagwat2006@gmail.com

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
