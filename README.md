🌱 Crop Heat-Stress Warning System

📌 Project Overview

The Crop Heat-Stress Warning System is a low-cost electronic monitoring system designed to detect temperature conditions that may cause heat stress in crops. It uses an NTC thermistor and LM358 operational amplifier comparators to monitor temperature and provide visual and audible warnings.

The system uses three LED indicators to represent different temperature conditions. A buzzer provides an additional warning when the temperature exceeds the critical threshold.

🎯 Problem Statement

High temperatures can negatively affect crop growth, plant health, and agricultural productivity. Farmers may not always have access to affordable temperature monitoring systems that provide immediate alerts.

This project addresses the problem by developing a simple, low-cost electronic system that monitors temperature and alerts users when heat conditions become critical.

💡 Proposed Solution

The system measures temperature using an NTC thermistor. The sensor voltage is compared with preset reference voltages using LM358 comparator circuits.

Based on the detected temperature, the system activates the appropriate LED indicator:

- 🟢 Green LED: Normal temperature condition
- 🟡 Yellow LED: Temperature warning condition
- 🔴 Red LED and buzzer: High-temperature alert

📸 Project Photos

🟢 Normal Temperature Condition

Green LED indicates the normal temperature condition.

IMG-20261103-WA0009.jpg

🟡 Temperature Warning Condition

Yellow LED indicates that the temperature has reached the warning range.

IMG-20261103-WA0010.jpg

🔴 High Temperature Warning

Red LED indicates the high-temperature condition. The buzzer provides an audible warning.

IMG-20261103-WA0011.jpg

«Note: These image links work only if the matching image files are uploaded to the repository's main branch with these exact filenames.»

⚙️ Working Principle

1. The NTC thermistor senses the surrounding temperature.
2. The thermistor resistance changes with temperature.
3. The sensor circuit converts the resistance variation into a voltage variation.
4. The LM358 comparator circuits compare the sensor voltage with preset reference voltages.
5. The corresponding LED indicates the temperature condition.
6. When the temperature exceeds the critical threshold, the red LED and buzzer are activated.

🌡️ Temperature Indication

Temperature| Indication| Condition
Below 30°C| 🟢 Green LED| Normal
30°C–35°C| 🟡 Yellow LED| Warning
Above 35°C| 🔴 Red LED + Buzzer| High-temperature alert

The thresholds are preset values for this prototype and can be adjusted according to crop requirements.

🔧 Components Required

- LM358 operational amplifier IC – 2
- NTC thermistor – 1
- Resistors
- Potentiometers
- Green LED
- Yellow LED
- Red LED
- Active buzzer
- Breadboards
- Jumper wires
- 5V power supply

✨ Features

- Low-cost temperature monitoring
- Three-level temperature indication
- Visual warning using LEDs
- Audible alert using a buzzer
- Simple analog circuit
- Adjustable temperature thresholds
- Suitable for educational and prototype applications

🌾 Applications

- Agricultural temperature monitoring
- Greenhouse temperature warning
- Small-scale crop monitoring
- Plant research and demonstration
- Electronics and sensor-based projects

🚀 Future Scope

- Integration with Arduino or ESP32
- Digital temperature display
- Wireless notification using Wi-Fi
- Mobile application monitoring
- Solar-powered operation
- Data logging and temperature history
- Crop-specific temperature thresholds

📚 Project Impact

This project demonstrates how basic electronic components can be used to monitor environmental conditions and provide early warnings. It offers an educational prototype for exploring sensor circuits, comparator operation, and agricultural monitoring.

🏫 Project Information

Department: Electronics and Communication Engineering (ECE)
Project Title: Crop Heat-Stress Warning System
Project Type: Analog Electronics / Sensor-Based Monitoring
Power Supply: 5V

👩‍💻 Author

Satveka

📝 License

This project is intended for educational and academic purposes.
