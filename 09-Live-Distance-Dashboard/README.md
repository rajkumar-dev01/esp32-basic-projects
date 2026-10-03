# 09-Live-Distance-Dashboard

An ESP32-based live distance monitoring project using an HC-SR04 ultrasonic distance sensor and a web server hosted on the ESP32.

The measured distance is displayed on a self-refreshing web page.

## Features

- HC-SR04 ultrasonic distance measurement
- ESP32 WiFi connectivity
- Web server hosted on ESP32
- Live distance monitoring
- Self-refreshing web dashboard
- Serial Monitor distance output
- Wokwi simulation

## Components

- ESP32
- HC-SR04 Ultrasonic Sensor

## Pin Connections

| HC-SR04 | ESP32 |
|---------|-------|
| VCC | 5V |
| TRIG | GPIO 5 |
| ECHO | GPIO 18 |
| GND | GND |

## Output

The Serial Monitor displays the measured distance in centimeters.

Example:

Distance: 145.2 cm  
Distance: 91.8 cm  
Distance: 191.7 cm  
Distance: 284.4 cm

The ESP32 also hosts a web page that displays the live distance reading.

## Wokwi Simulation

[Run the Live Distance Dashboard simulation](https://wokwi.com/projects/476833510869060609)
