# 🏠 Smart Intercom System Using Raspberry Pi, Arduino and Telegram Bot

## 📌 Overview

This project presents an IoT-based Smart Door Access Control System that allows a homeowner to monitor and control door access remotely. When a visitor presses the doorbell, the Raspberry Pi captures the visitor’s image using the PiCamera and instantly sends it to the owner through a Telegram Bot. The user can remotely grant or deny access using mobile commands.

The system improves security, prevents unauthorized entry, and enables real-time monitoring from anywhere using a smartphone.

---

## 🎯 Objectives

* Provide remote door monitoring
* Enhance home security
* Allow door control from anywhere
* Replace traditional doorbell systems with smart automation

---

## 🛠 Technologies Used

* Python
* Raspberry Pi
* Arduino UNO
* Serial Communication (UART)
* Telegram Bot API
* PiCamera Module
* Embedded Systems
* Internet of Things (IoT)

---

## ⚙️ System Working

1. Visitor presses the doorbell button.
2. Arduino detects the button press.
3. Arduino sends **"button_pressed"** message to Raspberry Pi.
4. Raspberry Pi captures the visitor image using PiCamera.
5. Image is sent to the homeowner via Telegram Bot.
6. Owner receives notification on mobile phone.
7. Owner sends command:

   * `/open` → Door opens
   * `/deny` → Access rejected
8. Raspberry Pi sends command to Arduino through serial communication.
9. Arduino performs the action using servo motor, LCD, buzzer and LED indicators.

---

## 💻 Python Program Responsibilities

* Detects signal from Arduino
* Captures visitor image
* Sends notification through Telegram Bot
* Receives user commands
* Sends control instructions to Arduino

---

## 🔌 Arduino Responsibilities

* Detects doorbell press
* Sends signal to Raspberry Pi
* Controls servo motor (door open/close)
* Displays status on LCD
* Activates buzzer and RGB LED indicators

---

## 📷 Output

* Visitor image sent to Telegram
* Remote door control using mobile phone
* LCD shows door status
* LED and buzzer indicate action

---

## ▶️ How to Run the Project

1. Install Python 3.9 or above
2. Install required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Create a Telegram Bot using BotFather
4. Add your bot token in the Python file
5. Connect Arduino to Raspberry Pi using USB
6. Run the program:

   ```
   python main.py
   ```

## 🎯 Applications

* Smart Homes
* Apartments
* Hostels
* Office Entry Systems
* Remote Security Monitoring

---

## 👨‍💻 Author

N.Rajeshwar Rao
B.Tech – Electronics and Communication Engineering
Interested in Python Development and Data Analysis

.
