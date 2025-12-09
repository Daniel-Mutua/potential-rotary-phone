[README.md](https://github.com/user-attachments/files/24055191/README.md)
# GSM SMS Test Project

## Overview

This project demonstrates how to send SMS messages using a GSM module
(SIM800/900 series) connected to an Arduino-compatible microcontroller.
It provides a simple test sketch that initializes the GSM module, checks
connectivity, and sends predefined SMS messages.

## Features

-   Initializes GSM module through serial communication.
-   Sends SMS to a configured phone number.
-   Basic error handling for GSM responses.
-   Easy-to-understand code structure suitable for beginners learning
    GSM communication.

## Hardware Requirements

-   Arduino board (e.g., Arduino Uno, Mega, or ESP32 depending on your
    setup)
-   SIM800L/SIM900 GSM module
-   Active SIM card
-   Power supply capable of providing 2A peak current for GSM module
-   Jumper wires and breadboard

## Software Requirements

-   Arduino IDE (latest version recommended)
-   GSM library (depending on your module)

## How to Use

1.  Connect the GSM module to your Arduino:
    -   TX → RX
    -   RX → TX
    -   GND → GND
    -   VCC → Appropriate power source
2.  Upload the provided `GSM_SMS_Test.ino` sketch.
3.  Open Serial Monitor.
4.  Wait for the module to initialize.
5.  The system will send an SMS automatically or on command, depending
    on the code.

## File Included

-   `GSM_SMS_Test.ino` -- Main Arduino sketch for testing SMS
    functionality.

## Notes

-   Ensure your SIM card has sufficient airtime.
-   Signal strength may affect GSM initialization.
-   Some networks require disabling PIN lock on SIM card.

## License

This project is released under the MIT License. You may use, modify, and
distribute it freely.
