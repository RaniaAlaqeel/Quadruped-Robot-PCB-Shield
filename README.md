# Quadruped Robot PCB Shield

This repository contains the custom Printed Circuit Board (PCB) design files for a quadruped robot. The board was designed using EasyEDA and acts as a dedicated shield for an Arduino Nano, providing organized power distribution and signal routing for servo motors and sensors.

## Hardware Features

* Microcontroller: Arduino Nano V3.
* Actuators: 4x Servo motor headers (VCC, GND, Signal) routed to digital pins D5, D6, D9, and D10.
* Sensor: MPU6050 (Accelerometer and Gyroscope) for balancing and motion tracking, connected via I2C (A4, A5).
* Power Management: Integrated MT3608 DC-DC boost converter to stabilize the voltage supplied from the battery to the servo motors and the microcontroller.

## Project Visuals

### 1. Schematic Diagram
The schematic defines the logical connections, power lines, and grounding of all components before the physical layout phase.
![Schematic](https://github.com/user-attachments/assets/55e4dc5a-d19d-4900-83aa-8fc90039f5bb)

### 2. 2D PCB Layout
The 2D layout demonstrates the physical routing of the dual-layer PCB, showing the top and bottom copper traces.
![2D PCB Layout](https://github.com/RaniaAlaqeel/Quadruped-Robot-PCB-Shield/blob/main/5765081533264891903.jpg)

### 3. 3D Render
The 3D render verifies the physical footprint, component placement, clearances, and overall form factor before sending the design to fabrication.
![3D View](https://github.com/RaniaAlaqeel/Quadruped-Robot-PCB-Shield/blob/main/5765081533264891904.jpg)

## Fabrication

The manufacturing-ready Gerber files are included in this repository. The zip file can be directly uploaded to any standard PCB manufacturer (such as JLCPCB) for production.

* Fabrication File: [Download Gerber File](https://github.com/RaniaAlaqeel/Quadruped-Robot-PCB-Shield/blob/main/Gerber_PCB-for-robotic-dog_PCB_PCB-for-robotic-dog_2026-08-15.zip)
