# Meat-Freshness-Detection-System

### Tagline
Detecting the freshness of meat using an Arduino board, TCS34725 color sensor, and LCD display.

---

## Introduction

### What is this project?
This project utilizes an Arduino board, a TCS34725 color sensor, and an LCD display to detect the freshness of meat. The color sensor measures the RGB values of the meat, and the Arduino board processes these values to determine the freshness. The results are shown on an LCD display.

### Why was this project created?
This project was developed to offer a simple and cost-effective way to determine meat freshness. Its applications include food quality control, meat processing, and food safety.

---

## Key Features
- **RGB Measurement**: Measures the RGB values of meat using the TCS34725 color sensor.
- **Freshness Detection**: Determines the freshness of meat based on the RGB values.
- **LCD Display Output**: Displays the freshness result on an LCD display.
- **Air Quality Monitoring**: Includes an air quality sensor that monitors and displays air quality.

---
## Connections
- ### 1. TCS34725 Color Sensor to Arduino:
| **TCS34725 Pin** | **Arduino Pin** |
|------------------|-----------------|
| VIN              | 5V              |
| GND              | GND             |
| SDA              | A4 (SDA)        |
| SCL              | A5 (SCL)        |

### 2. LCD Display to Arduino:
| **LCD Pin** | **Arduino Pin** |
|-------------|-----------------|
| VCC         | 5V              |
| GND         | GND             |
| SDA         | A4 (SDA)        |
| SCL         | A5 (SCL)        |

### 3. Air Quality Sensor to Arduino:
| **Air Quality Sensor Pin** | **Arduino Pin** |
|----------------------------|-----------------|
| VCC                        | 5V              |
| GND                        | GND             |
| OUT                        | A0              |

### 4. Breadboard and Jumper Wires:
- Use jumper wires to connect all components to the breadboard and Arduino for proper grounding and power distribution.


---

## Screenshots
- **Circuit Diagram**
  ![Connections](https://github.com/user-attachments/assets/110b1fe1-d726-48c6-9d17-534d644ebe10)

  
- **LCD Display Output**  
  ![LCD output](https://github.com/user-attachments/assets/2362888e-f8fa-400d-98ec-a9ddf653ce19)


  

---

## Getting Started

### Prerequisites
- Arduino Board
- TCS34725 Color Sensor
- LCD Display
- Air Quality Sensor
- Breadboard and jumper wires for connections

### Installation

1. Connect the TCS34725 color sensor to the Arduino board as shown in the circuit diagram.
2. Connect the LCD display to the Arduino board as shown in the circuit diagram.
3. Connect the air quality sensor to the Arduino board as shown in the circuit diagram.
4. Upload the code to the Arduino board using the Arduino IDE.

### Usage
1. Place the meat sample in front of the color sensor.
2. The Arduino will measure the RGB values of the meat and determine its freshness.
3. The result will be displayed on the LCD display.
4. The air quality sensor will also measure and display the air quality value on the serial monitor.

---
