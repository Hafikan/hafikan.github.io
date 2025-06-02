---
name: Urban Air Traffic Management with Droneport and GSM-Based Communication

tools: [UAV Development, 4G, LTE, STM32, AWS CLOUD, Python, C, C++, JavaScript, Reverse Engineering]
image: https://adaguzey.com/wp-content/uploads/2024/05/Droneport.jpg
description: My contributions to this project included the development of an innovative droneport system that facilitates efficient takeoff and landing operations for drones. Additionally, I designed GSM-based communication software to ensure seamless interaction between the drones, the droneport, and the central computer. 
---
# 4G/LTE-Based Smart Droneport and CoPilot Control System

This project involved the development of an intelligent droneport system tailored for urban delivery drones, along with a custom-designed 4G/LTE-based communication protocol. The system enables autonomous and secure data exchange between drones, the droneport, and a user interface with approximately 200 ms latency. The Co-Pilot interface, built with Qt and Python, empowers users with both manual and autonomous mission control capabilities.



![preview](/assets/dron_port_1.png)

Key Features:
Modular Communication Protocol
A layered protocol was developed to manage flight telemetry, mission commands, status updates, and time synchronization between drone, droneport, and the user interface. It includes advanced security algorithms to ensure connection reliability and data integrity.

🔹 Extended Range via LTE Connectivity
Unlike conventional RF-based solutions, the LTE infrastructure provides extended control range and high-speed, low-latency communication. The system supports remote access and allows operators to intervene in real time via the Co-Pilot interface.

🔹 Qt-Based CoPilot Interface

Map-based mission definition and route planning

Real-time telemetry visualization

Live logging and fault notification system

Seamless transition between manual and autonomous control

Automatic mission recovery after reboot or system restart

🔹 Intelligent Droneport Hardware
The droneport's control unit is built on an Atmel AVR microcontroller, utilizing PID-based motor control algorithms for precise landing platform stabilization. The station supports LTE and can be remotely accessed and managed over the network.
An onboard self-diagnostic software module monitors the system status and reports issues proactively.

