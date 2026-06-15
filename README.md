##ESP32-Model-Railway-Track-Controller

<img width="683" height="621" alt="RAILWAY " src="https://github.com/user-attachments/assets/37b8e8a7-7365-4695-b603-3bb15a4a41de" />

##Project Overview

This project was developed for a private model railway enthusiast who required a dedicated controller for switching 24 track points distributed across a large home railway layout. Instead of using a complex DCC ecosystem, a custom ESP32 controller was designed to provide:

* Wi-Fi-based control
* Servo-driven point switching
* Individual servo calibration
* Web application integration
* Scalable multi-board architecture
* Reliable and repeatable operation
The final system consists of three custom ESP32 boards, each capable of controlling eight servo motors independently.
ESP32-based Wi-Fi railway track controller for managing 24 servo-driven track points with custom PCB hardware, firmware, and web control. <a href="https://digitalmonk.biz/hire-arduino-developer/">Arduino Coder for Hire</a>
--

##Hardware Features
<img width="449" height="373" alt="RAILWAY01" src="https://github.com/user-attachments/assets/d5c2ad62-d5ee-404a-b5ae-6549c331b992" />

* ESP32 microcontroller with integrated Wi-Fi
* Custom PCB design
* 8 servo channels per controller board
* USB-C powered (12V input)
* Onboard voltage regulation
* Modular and expandable architecture
* Independent servo control outputs
* Designed for long-term reliability
--

##Software Features
* Custom ESP32 firmware
* Real-time Wi-Fi communication
* Node.js API integration
* Remote web-based operation
* Instant command execution
* Multi-board device addressing
* Firmware-level safety protections
--

##Key Challenges Solved
Accurate Servo Calibration
Each railway point requires unique movement limits due to different linkage geometries and mechanical tolerances. The firmware stores individual settings for:
* Straight position angle
* Diverging position angle
* Minimum limits
* Center position
* Maximum travel limits
This prevents servo over-rotation and protects both the servo mechanism and railway point hardware.
--

### Reliable Remote Operation
The controller connects directly to the layout's Wi-Fi network, allowing users to control track points using smartphones, tablets, or desktops without requiring dedicated hardware controllers.
--

##System Architecture
Web Application
        │
        ▼
    Node.js API
        │
        ▼
     Wi-Fi Network
        │
 ┌──────┼──────┐
 ▼      ▼      ▼
Board1 Board2 Board3
 │       │      │
8 Servos 8 Servos 8 Servos
```
--

##Benefits
<img width="454" height="487" alt="RAILWAY02" src="https://github.com/user-attachments/assets/c4809a30-693a-4b8e-bdc8-ff6814b31f4e" />

* Eliminates manual track switching
* Easy web-based control
* Precise and repeatable operation
* Expandable system architecture
* Reduced wiring complexity
* Protection against servo damage
* Customizable for different railway layouts
--

##Project Highlights
| Feature                  | Value      |
| ------------------------ | ---------- |
| Microcontroller          | ESP32      |
| Controlled Track Points  | 24         |
| Servo Channels per Board | 8          |
| Number of Boards         | 3          |
| Connectivity             | Wi-Fi      |
| Power Input              | 12V USB-C  |
| Delivery Time            | 16–18 Days |
--

##Technologies Used
* ESP32
* Embedded C/C++
* Custom PCB Design
* Servo Motor Control
* Wi-Fi Communication
* Node.js
* REST API
* Web Application Integration
--

##Results
The completed solution enables seamless control of all 24 track points from any device connected to the local network. Each servo is individually calibrated, ensuring accurate movement and long-term reliability while maintaining a simple and user-friendly operating experience.
--


