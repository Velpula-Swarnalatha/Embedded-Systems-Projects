# RFID Attendance System

## Components

- PIC16F877A
- EM18 RFID Reader
- 16x2 LCD
- LED
- UART
- Power Supply

## Function

The system reads the RFID card using the EM18 RFID reader and sends the RFID data to the PIC16F877A through UART.

- Valid RFID card → Access Granted
- Invalid RFID card → Access Denied
- LCD → Displays the access status
- LED → Indicates the access status
