# IoT Based Smart-Energy-Monitoring-System-with-Real-Time-Telegram-Alerts Using esp-32

The increasing demand for real-time electricity monitoring has driven the need for smart 
metering solutions that enhance energy efficiency and user accessibility. This project 
presents the development of an IoT-based Smart Electricity Energy Meter utilizing the 
ESP32 microcontroller and the Telegram app for remote monitoring. By incorporating 
high-precision sensors—SCT-013 for current measurement and ZMPT101B for voltage 
detection—the system accurately measures voltage, current, power, and total energy 
consumption in kilowatt-hours (kWh). The collected data is displayed in real-time on both 
an LCD and the Telegram app, allowing users to monitor their electricity usage remotely. 
This smart metering solution aims to improve monitoring electricity consumption, promote 
energy conservation, and facilitate data-driven decision-making for users. 

## Ciruit Diagram:

![Screenshot 2025-05-16 105801](https://github.com/user-attachments/assets/618e80c6-74d9-4b61-9c2e-02a83dd9701e)

## Telegram Alerts
![Screenshot 2025-05-16 110626](https://github.com/user-attachments/assets/5c50fde3-6554-4c98-a54e-6e416a422ad9)

## Block Digaram
![Screenshot 2025-05-16 110956](https://github.com/user-attachments/assets/8c529330-4ce8-4c2b-9784-073be4566d38)

##  Features
- Real-time monitoring of voltage, current, power, and energy (kWh)
- IoT-enabled with ESP32 and Wi-Fi
- Instant Telegram alerts with energy usage updates
- LCD display for local status visualization
- Low-cost and scalable hardware design
- Promotes energy conservation through awareness
  
##  Hardware Components
- ESP32-WROOM-32 Development Board
- SCT-013 Current Sensor
- ZMPT101B Voltage Sensor
- 16x2 LCD Display (with I2C module)
- Resistors, connecting wires, breadboard

## Software & Libraries Used

- Arduino IDE
- `LiquidCrystal_I2C.h` – for LCD
- `WiFi.h` – ESP32 Wi-Fi connection
- `UniversalTelegramBot.h` – Telegram Bot API
- `EmonLib.h` – Energy Monitoring Library

## How to Run

1. Clone this repo
2. Install required libraries in Arduino IDE
3. Open the `.ino` file
4. Enter your Wi-Fi credentials and Telegram bot token
5. Upload to ESP32 and monitor the Serial output
6. Start receiving real-time updates on your Telegram app

## Future Scope

- Firebase integration for data logging
- Energy usage prediction with ML models
- Web dashboard for historical data trends
- Relay module to auto-cut power on overload

