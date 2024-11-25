# Real-time Air Traffic Monitoring and Control System
This project implements a Real-Time Air Traffic Monitoring and Control (ATC) System in C/C++, designed for execution on the QNX real-time operating system x86 virtual machine.

This is a simplified en-route ATC system to ensure safe, orderly aircraft movement. This involves maintaining adequate separation between aircraft, detecting potential conflicts, and responding in real time using threads to ensure the proper execution of all functions.

## Features:
### Ensure safety:
- Monitor airspace for adequate aircraft separation (min. 1000 units vertically, 3000 units horizontally).
- Alert controllers of potential collisions or safety violations through inter-process communication.
### Provide Real-Time Visualization:
- Periodically display aircraft positions and notify controllers of safety-critical situations.
### System Logging:
- Record airspace history and operator commands for analysis and troubleshooting.
### Support Operator Commands:
- Enable ATC controllers to direct aircraft to modify speed, altitude, or position.
