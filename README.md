# DIY Treadmill Automation Project

https://youtu.be/V_Q4gVCC9HE

Description:

This project aims to automate a treadmill using two ESP01-S microcontrollers with Tasmota firmware, a motion sensor (MH-SR602), and four Relay-v4.0 modules. The automation is controlled by Home Assistant.

The automation system is designed to detect the presence of a person on the treadmill and automatically start the treadmill. The motion sensor is used to detect the presence of a person, and once detected, it sends a signal to the microcontroller to activate the treadmill.

The system can also be controlled manually using a Home Assistant interface. The user can start or stop the treadmill, adjust the speed, and monitor the status of the system.

To implement the project, the microcontrollers were first flashed with Tasmota firmware to enable communication with Home Assistant. The motion sensor was connected to one of the microcontrollers, while the Relay modules were connected to the other microcontroller. The microcontrollers were then integrated into Home Assistant, and a custom automation script was created to control the system.

This repository contains the code and instructions needed to replicate the project, including the Home Assistant automation script and video documentation of the system in action.
