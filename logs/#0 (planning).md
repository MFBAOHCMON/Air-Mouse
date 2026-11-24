# Devlog 0
planning phase

Date: November 11, 2026 (forgot to write the planning devlog back then but that's when we finished planning)

## Project Overview

Our goal is to make a wireless mouse that can translate 3d movement into 2d cursor movements and rotation(pitch, yaw, roll) based on the program. Using our ESP32-C3 and MPU-6050 as our main parts, we can achieve these features :
- Wireless HID: the ESP32-C3 allows for us to emulate a standard bluetooth mouse
- Smooth Tracking: eliminates jittering and sensor drift
- Power Effeciency: uses the ESP32-C3's deep sleep modes to extend battery life


## Bill Of Material(BOM)

| Function | Part | Cost($) | Source |
| :--- | :---: | :---: | --: |
Microcontroller | ESP32-C3 Supermini Development Board | 1.75 | aliexpress.com/item/1005007010555229.html? |
IMU | MPU6050 3-Axis Gyroscope + 3-Axis Accellerometer | 1.67 | aliexpress.com/item/1005008410293134.html? |
Input | Push Button | 2.28 | http://amazon.ca/Momentary-Button-Tactile-6x6x5mm-Keaiduoa/dp/B07T3Q686Y? |
TOTAL COST|   | 5.7|   |


## Pin Mapping

| ESP32-C3 Pinning | Connected Part | Function Description |
| :--- | :---: | ---: | 
| GPIO 5 | MPU6050 SDA | I2C Data Line | 
| GPIO 4 | MPU6050 SCL | I2C Clock Line |
| GPIO 3 | Left Tactile Switch | Left Click / Scroll Down |
| GPIO 2 | Right Tactile Switch | Right Click / Scroll Up |
| 3.3V | MPU6050 VCC | Power |
| GND | MPU6050 GND & Switch GND | Ground |
