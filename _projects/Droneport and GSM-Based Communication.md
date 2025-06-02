---
name: Urban Air Traffic Management with Droneport and GSM-Based Communication

tools: [UAV Development, 4G, LTE, Atmel AVR Programming, AWS CLOUD, Python, C, C++, JavaScript, Reverse Engineering]
image: https://adaguzey.com/wp-content/uploads/2024/05/Droneport.jpg
description: My contributions to this project included the development of an innovative droneport system that facilitates efficient takeoff and landing operations for drones. Additionally, I designed GSM-based communication software to ensure seamless interaction between the drones, the droneport, and the central computer. 
---
# 4G/LTE-Based Droneport, Quad-Copter and CoPilot Control System

This project involved the development of an intelligent droneport system tailored for urban delivery drones, along with a custom-designed 4G/LTE-based communication protocol. The system enables autonomous and secure data exchange between drones, the droneport, and a user interface with approximately 200 ms latency. The Co-Pilot interface, built with Qt and Python, empowers users with both manual and autonomous mission control capabilities.


![preview](/images/2025-06-02_15-25.png)


## Used Technologies
**Languages & Frameworks**
<ul>

<li>C++ – Embedded firmware development for droneport control unit (AVR)</li>

<li>Python – Backend logic for Co-Pilot interface and data processing</li>
<li>JavaScript – Open Street Map Sockets for Co-Pilot Navigation Interface</li>
<li>Qt (PyQt5) – UI/UX development of the Co-Pilot mission control interface</li>
</ul>


**Protocols & Communication**
<ul>

<li>Custom 4G/LTE Communication Protocol – Low-latency, secure telemetry and command exchange</li>

<li>UART, I2C – Hardware communication between sensors and controllers</li>

<li>Socket Programming (TCP/IP) – Network communication for telemetry and control commands</li>

<li>AWS Instances - For data tunnels between Drone & CoPilot Display & Dron Port</li>

</ul>

**Embedded Systems & Electronics**

<ul>
<li>Atmel AVR Microcontroller – Motor control and system logic on droneport hardware</li>
<li>PID Control Algorithms – Stable platform positioning for drone landing</li>
</ul>

**Other Tools & Concepts**

<ul>


<li>Real-Time Logging & Diagnostics – Live error reporting and telemetry monitoring</li>

<li>GPS-Based Navigation – Map integration and route planning</li>

<li>State Machine Design – Autonomous behavior flow and system recovery logic</li>
</ul>

![preview](/images/2025-06-02_15-26.png)

## Key Features:


**Modular Communication Protocol**

A layered protocol was developed to manage flight telemetry, mission commands, status updates, and time synchronization between drone, droneport, and the user interface. It includes advanced security algorithms to ensure connection reliability and data integrity.

**Extended Range via LTE Connectivity**

Unlike conventional RF-based solutions, the LTE infrastructure provides extended control range and high-speed, low-latency communication. The system supports remote access and allows operators to intervene in real time via the Co-Pilot interface.

**Qt-Based CoPilot Interface**

<ul>

    <li>Map-based mission definition and route planning</li>
    
    <li>Real-time telemetry visualization</li>

    <li>Live logging and fault notification system</li>

    <li>Seamless transition between manual and autonomous control</li>

    <li>Automatic mission recovery after reboot or system restart</li>
    
</ul>


**Intelligent Droneport Hardware**

The droneport's control unit is built on an Atmel AVR microcontroller, utilizing PID-based motor control algorithms for precise landing platform stabilization. The station supports LTE and can be remotely accessed and managed over the network.
An onboard self-diagnostic software module monitors the system status and reports issues proactively.

![preview](/images/2025-06-02_15-26_1.png)

**Areas for Improvement**
<ul>

<li>LTE dependency may limit performance in poor coverage areas</li>

<li>Atmel AVR controller may impose processing constraints on complex tasks</li>

<li>The 200 ms latency could be further optimized for time-critical missions</li>

</ul>


