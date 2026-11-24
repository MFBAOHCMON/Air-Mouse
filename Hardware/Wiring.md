# HardWare Wiring
This file talks about specifics on how my project is wired as well as an illustration on it <3


## Pin Mapping

| ESP32-C3 Pinning | Connected Part | Function Description |
| :--- | :---: | ---: | 
| GPIO 5 | MPU6050 SDA | I2C Data Line | 
| GPIO 4 | MPU6050 SCL | I2C Clock Line |
| GPIO 3 | Left Tactile Switch | Left Click / Scroll Down |
| GPIO 2 | Right Tactile Switch | Right Click / Scroll Up |
| 3.3V | MPU6050 VCC | Power |
| GND | MPU6050 GND & Switch GND | Ground |


## Wiring Illustration

<img width="557" height="529" alt="Wiring" src="https://github.com/user-attachments/assets/16d35d7f-c5c0-4539-9e40-e5a0f53bfb58" />
