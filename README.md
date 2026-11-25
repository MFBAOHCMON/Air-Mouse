# AIR-MOUSE README
This repository talks about my 'air-mouse' project! I will be including the wiring, how it works, and more(maybe) :D


## HOW IT WORKS

This project works by utilizing an ESP32-C3 supermini development board and a MPU-6050.

### ESP32-C3
- Acts as the "brain" of the Air-mouse
- Provides a BLE HID output so you device recognizes it as a Bluetooth device
- Calculates cursor movement
- And much more!

### MPU-6050
- Detects linear motion and sends information to the ESP32-C3
- Measures rotation(pitch, roll, and yaw)
- Uses it's built in ADCs to turn motion into digital values
- And much more!

## Bill Of Material(BOM)

| Function | Part | Cost($) | Source |
| :--- | :---: | :---: | --: |
Microcontroller | ESP32-C3 Supermini Development Board | 1.75 | http://aliexpress.com/item/1005007010555229.html? |
IMU | MPU6050 3-Axis Gyroscope + 3-Axis Accellerometer | 1.67 | http://aliexpress.com/item/1005008410293134.html? |
Input | Push Button | 2.28 | http://amazon.ca/Momentary-Button-Tactile-6x6x5mm-Keaiduoa/dp/B07T3Q686Y? |
TOTAL COST|   | 5.7|   |


## WIRING

<img width="557" height="529" alt="Wiring" src="https://github.com/user-attachments/assets/48bfd3ff-6c95-4556-9683-d5009ddd36e8" />


## MORE!

This project has been created without the use of ANY ai
