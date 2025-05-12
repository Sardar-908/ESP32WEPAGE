# 🌐 ESP32 IoT-Based Real-Time Control and Monitoring System

A collaborative project by **Team VEGA** as part of our internship, under the mentorship of the **LearnSquare** team.

This project uses the **ESP32 Trainer Kit** to integrate sensors and actuators for real-time monitoring and control through a web interface hosted on a local server.

---

## 🚀 Features

- **Sensor Integration**
  - 📷 LDR – Light Intensity Monitoring
  - 📏 Ultrasonic Sensor – Distance Measurement

- **Actuators & Indicators**
  - 🔔 Buzzer – Alert System
  - 💡 LEDs – Visual Notifications

- **Local Web Server**
  - View sensor data in real time
  - Submit control inputs via web form
  - Accessible across devices on the same Wi-Fi network

- **OLED Display**
  - Live data visualization on the device

- **Future Scope (Optional Enhancements)**
  - Data logging to CSV/SPDIF/Cloud (Firebase or SD card)

---

## 🧰 Hardware Used

| Component            | Quantity |
|----------------------|----------|
| ESP32 Dev Module     | 1        |
| LDR Sensor           | 1        |
| Ultrasonic Sensor    | 1        |
| Passive Buzzer       | 1        |
| LEDs (Generic)       | 2 or more|
| OLED Display (I2C)   | 1        |
| Jumper Wires, Breadboard, Resistors | As required |

---

## 💻 Software & Libraries

- Arduino IDE / PlatformIO
- `ESPAsyncWebServer` and `AsyncTCP` (Web server)
- `Adafruit SSD1306` (OLED display)
- `Wire.h` (I2C communication)

---

## 🛠️ Setup Instructions

1. **Hardware Connections**
   - Connect all sensors and output devices to ESP32 GPIO pins (refer to circuit diagram)

2. **Code Configuration**
   - Install necessary libraries in Arduino IDE
   - Set your Wi-Fi SSID and Password in the code

3. **Upload & Run**
   - Upload the code to your ESP32 board
   - Monitor Serial Output to get the IP Address

4. **Interact via Web**
   - Open the IP address on any device browser connected to the same Wi-Fi
   - Monitor values and control buzzer/LED from the form
   - Watch data update on OLED display

---

## 👨‍💻 Team Members – Team VEGA

- [Jagadeeshwar Sreeram](https://www.linkedin.com/in/jagadeeshwar-sreeram)

## 🙏 Acknowledgements

- Huge thanks to **LearnSquare** for the hands-on mentorship and hardware training.
- Inspired by practical use cases in **Home Automation**, **Smart Alerts**, and **Edge IoT Applications**.

---

## 📬 Contact

Have questions, suggestions, or feedback?

📧 Email: **jagadeeshwar270@gmail.com**  
📩 DM me on [LinkedIn](https://www.linkedin.com/in/jagadeeshwar-sreeram)

---
