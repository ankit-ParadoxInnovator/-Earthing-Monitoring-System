# -Earthing-Monitoring-System
Its my Smart Indian Hackathon project

The Earthing Monitoring System is an IoT-based safety solution designed to continuously monitor the health and effectiveness of earthing in street poles and electrical networks. It detects faults, leakage currents, and abnormal earthing resistance in real time to prevent electrical hazards.

The system consists of:

Pole Circuit: Installed on each pole to measure parameters like line voltage, current, leakage, and earthing resistance using transformers and sensors. It also automates street lights and ensures local safety shutdowns in case of faults.

Substation Circuit: Collects data from all poles via radio communication, displays real-time pole status, and alerts through buzzer notifications.

Extender Module: Extends communication range between poles and substations when needed.

Server (Raspberry Pi 4): Stores and manages data securely, providing remote access through a web interface and mobile app.

Key Features:

Real-time earthing fault detection

Wireless data transmission (NRF 2.4GHz)

Automatic power cut during leakage

Remote monitoring via Wi-Fi and web dashboard

Self-hosted secure data server
