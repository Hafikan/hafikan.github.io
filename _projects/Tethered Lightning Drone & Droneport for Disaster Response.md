---
name: Tethered Lightning Drone & Droneport for Disaster Response

tools: [UAV Development, Energy Monitoring, Tethered Drones, Atmel AVR Programming, Python, C, C++,   ROS]
image: hafikan.github.io/images/OrnekGorsel.jpeg
description: This project focused on developing a tethered hexa-copter system and an associated smart droneport to meet the unique demands of disaster response scenarios, such as nighttime search and rescue, area illumination, and continuous aerial monitoring.
---
# Tethered Lightning Drone & Droneport System Prototype (Disaster Response)

This project focused on developing a tethered hexa-copter system and an associated smart droneport to meet the unique demands of disaster response scenarios, such as nighttime search and rescue, area illumination, and continuous aerial monitoring. The system was optimized for extended flight endurance, high-intensity lighting, and stable hovering performance, all powered through a physical tether that delivers both electricity and data.

![preview](/images/Kurtarma_Alanı-100.jpg)


## Used Technologies
**Languages & Frameworks**
<ul>

<li>C++ – Embedded firmware for droneport and power management</li>

<li>Python – Ground control station modules for data routing and diagnostics</li>

<li>Qt (PyQt5) – Simple UI for operator control</li>

</ul>


**Communication**
<ul>

<li>Custom Tethered Protocol – Real-time droneport-drone communication over physical line</li>

<li>RS485, RS432, I2C – Low-level communication between sensors and controllers</li>


</ul>

**Embedded Systems & Control**

<ul>
<li>Atmel AVR Microcontroller – Main controller for droneport functions</li>
<li>Energy Management Circuitry – Voltage/current monitoring and overload protection</li>
</ul>

**Concepts**

<ul>


<li>Architecture – Resilient system behavior and safe task transitions</li>

</ul>

![preview](/images/Deprem_alanı-100.jpg)

## Key Features:


**Tethered Energy and Data Transfer**

A secure, interference-resistant tether enables simultaneous power and data communication, ideal for stationary long-duration missions.

**Real-Time Telemetry Exchange**

A multi-layer protocol was implemented to ensure low-latency data exchange between drone and droneport, as well as with the Ground Control Station (GCS).

**Bidirectional Communication**

Communication between the onboard flight computer and GCS was successfully established via Python and C++ modules.


**State Recovery Logic**

In case of a system restart or interruption, the droneport resumes operations from the last known safe state using a state-machine-based control flow.

