# Web Controlled LEDs using NodeMCU (ESP8266)

This IoT project demonstrates how to control two LEDs using a web browser over WiFi with NodeMCU (ESP8266).

## Features
- Control LEDs from any device connected to the same WiFi
- Simple web interface
- Uses NodeMCU as a web server

## Components Used
- NodeMCU (ESP8266)
- 2 LEDs
- 2 × 330Ω Resistors
- Breadboard
- Jumper Wires

## Connections
- LED 1 Anode → D5 via 330Ω resistor  
- LED 2 Anode → D6 via 330Ω resistor  
- Both LED Cathodes → GND

## Working
1. NodeMCU connects to the given WiFi network.
2. It starts a web server on port 80.
3. When a button is clicked on the webpage, a GET request is sent.
4. Based on the request, LEDs are turned ON or OFF.

## Code
See `web_led_control.ino`

## Output
- Access the NodeMCU IP address in a browser.
- Control LEDs using ON/OFF buttons.

## Learning Outcome
- ESP8266 WiFi basics
- Web server creation
- HTTP GET request handling
- Real-time hardware control using web interface

---
Made by **Khushi Navalramani**
