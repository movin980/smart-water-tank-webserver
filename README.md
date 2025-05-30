
# Smart Water Tank Monitoring (ESP32 Web Server)

This project uses an **ESP32 microcontroller** and an **ultrasonic sensor (HC-SR04)** to monitor the water level of a tank in real-time.

The ESP32 runs a built-in **web server** that displays the water level as a percentage on a live dashboard, which can be accessed from any browser on the same Wi-Fi network.

## ✅ Features
- No external cloud or dashboard tools (no Blynk, no Firebase)
- Built-in ESP32 web server
- Shows water level (%) live on a webpage
- Works on both desktop and mobile browsers
- Refreshes every few seconds automatically

## 🧰 Hardware Used
- ESP32 Dev Board
- HC-SR04 Ultrasonic Sensor
- Breadboard + Jumper Wires
- Wi-Fi connection

## 📲 How to Use
1. Flash the code to your ESP32 using Arduino IDE
2. Connect to your Wi-Fi (update SSID/password in code)
3. Open the Serial Monitor to get the ESP32's IP address
4. Open that IP in a browser to see your smart tank dashboard

## 🔧 Future Improvements
- Add historical data logging
- Add warning system (LED/Buzzer)
- Add graphical water gauge

