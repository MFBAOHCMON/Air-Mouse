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


## WIRING

<img width="557" height="529" alt="Wiring" src="https://github.com/user-attachments/assets/48bfd3ff-6c95-4556-9683-d5009ddd36e8" />


## MORE!

This project has been created without the use of ANY ai
