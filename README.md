# CAN-TestBed

The CAN-TestBed is a hands-on tool designed to teach car network security. It connects real hardware to a web dashboard, effectively creating a "virtual car" on your desk. 

This tool allows students and researchers to replay authentic CAN traffic logs (`candump`), configure hardware-level ID filtering, and perform real-time security assessments by simulating attacks like ID spoofing and Denial of Service (DoS) in a safe, controlled environment.

## Documentation Pages

| Page | Subsections (Quick Links) | Description |
| :--- | :--- | :--- |
| **Initial Setup** | • [Hardware Setup](docs/Install-Setup.md#hardware-setup)<br>• [Software Setup](docs/Install-Setup.md#software-setup) | Guide for setting up the RP2040/CANable hardware and installing the Python/Node.js environment. |
| **Using the TestBed** | • [Normal Simulation](docs/Using-the-TestBed.md#normal-simulation)<br>• [Attack Simulation](docs/Using-the-TestBed.md#attack-simulation) | Instructions on connecting devices, running normal traffic, and using the injection panel to simulate attacks. |
| **Student Labs** | • [Firmware Mitigation](docs/Student-Labs.md#firmware-mitigation) | Educational exercises on modifying `CANBed.ino` to implement message encryption and authentication. |
