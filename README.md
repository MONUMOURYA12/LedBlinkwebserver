ESP32 Web-Based LED Control (SoftAP Mode)

This project demonstrates a standalone ESP32 web server that controls two LEDs through a webpage interface.
The ESP32 operates in Soft Access Point (SoftAP) mode, meaning it creates its own Wi-Fi network and does not require any external router or internet connection.

Users can connect directly to the ESP32 using a mobile phone or laptop and control the LEDs using on-screen buttons.

🚀 Features

ESP32 runs as a Wi-Fi Access Point

No router / no internet required

Control two LEDs via any web browser

Real-time ON / OFF status display

Simple and lightweight embedded HTML & CSS

Ideal for college projects, demos, and IoT learning

🛠️ Technologies Used

ESP32 Development Board

Arduino IDE

WiFi.h

WebServer.h

HTML & CSS (embedded in code)

📡 How It Works

ESP32 creates its own Wi-Fi network (SoftAP mode)

User connects to the ESP32 Wi-Fi from phone or laptop

A web server runs on the ESP32

Webpage displays two buttons for LED control

Button clicks send HTTP requests to the ESP32

ESP32 toggles the LEDs accordingly

🔌 Circuit Diagram
Connections
ESP32 Pin	Component
GPIO 2	LED 1 (via 220Ω resistor)
GPIO 4	LED 2 (via 220Ω resistor)
GND	LED cathode (–)
USB	Power supply
Text Diagram
ESP32 GPIO2 ──[220Ω]──▶ LED1 ── GND
ESP32 GPIO4 ──[220Ω]──▶ LED2 ── GND

📲 How to Use

Upload the code to ESP32 using Arduino IDE

Power the ESP32 (USB / adapter / power bank)

Open Wi-Fi settings on phone or laptop

Connect to:

SSID: ESP32_LED
Password: 12345678


Open a browser and enter:

http://192.168.4.1


Use the buttons to control the LEDs

🧠 Wi-Fi Modes Used

Soft Access Point (SoftAP) Mode

ESP32 creates its own Wi-Fi

Acts as DHCP server and gateway

Suitable for restricted networks (college / hostel)

🎓 Learning Outcomes

Understanding ESP32 Wi-Fi modes

Creating a web server on ESP32

HTTP request handling

GPIO control via web interface

Embedded system + networking basics

📌 Use Cases

IoT beginner projects

College mini-projects

Offline device control

Embedded networking demonstrations
