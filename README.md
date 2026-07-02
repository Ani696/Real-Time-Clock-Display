# Real Time Clock Display using Arduino Uno

## Intern Details
- **Intern Name:** Aniket Srivastava
- **Intern ID:** CITS3416
- **Internship Duration:** 4 Weeks

## Project Overview
This project demonstrates a Real Time Clock (RTC) Display using an Arduino Uno, a DS1307 RTC module, and a 16×2 I2C LCD. The RTC module keeps track of the current date and time, while the LCD displays the information in real time.

## Components Used
- Arduino Uno
- DS1307 RTC Module
- 16×2 I2C LCD Display
- Jumper Wires
- Wokwi Simulator

## Pin Connections

### DS1307 RTC Module
| RTC Pin | Arduino Uno |
|----------|-------------|
| VCC | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

### 16×2 I2C LCD
| LCD Pin | Arduino Uno |
|----------|-------------|
| VCC | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

## Working Principle
- The DS1307 RTC module maintains the current date and time.
- The Arduino reads the RTC data every second.
- The 16×2 I2C LCD displays the current time on the first line and the current date on the second line.
- The display updates automatically every second.

## Software Used
- Arduino IDE
- Wokwi Simulator
- GitHub

## Project Files
- sketch.ino
- diagram.json
- wokwi.toml
- Circuit_Diagram.png

## Wokwi Simulation
Paste your Wokwi project link here.

## Author
**Aniket Srivastava**
