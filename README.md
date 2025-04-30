# Minesweepers 2021  Junior Category – Humanitarian Demining Robot

This repository contains the complete design, source code, and technical documentation for our autonomous robot developed for participation in the **Minesweepers Junior Category**. The robot is designed to detect and collect both **surface** and **buried landmines** in a simulated demining arena, in accordance with the official competition rules.

## About the Competition

**Minesweepers: Towards a Landmine-Free World** is an international robotics competition that aims to promote the development of innovative robotic solutions for **humanitarian demining**. The **Junior Category** encourages students to design fully autonomous ground robots capable of:
- Navigating a predefined arena
- Detecting surface and underground (metallic) mines
- Safely collecting and transporting detected mines to a designated disposal zone

## System Overview

The robot integrates multiple subsystems, including:
- **Mine Detection System**:
  - *Surface Mine Detection*: Utilizing color or object recognition sensors
  - *Buried Mine Detection*: Implemented through a metal detector module
- **Collection Mechanism**:
  - A mechanical gripper or actuator to securely collect and transport detected mines
- **Autonomous Navigation**:
  - Pre-programmed path following or reactive movement within the arena boundaries
- **Chassis and Drive System**:
  - A differential or omni-directional drive system powered by DC motors or servo motors

## Hardware Components

- **Microcontroller**: [e.g., Arduino Uno, ESP32]
- **Metal Detector Sensor**: For detection of underground metallic objects
- **Vision or IR Sensor**: For detecting surface mines
- **Gripper Mechanism**: Servo-controlled collector
- **Motor Drivers and Power Supply**: Appropriate motor driver ICs and battery pack
- **Chassis**: Custom-built frame with integrated electronics and drive system
- **Obstacle Avoidance (Optional)**: Ultrasonic sensors

## Software Architecture

- **Programming Language**: C++ (Arduino IDE) / MicroPython
- **Modules**:
  - Sensor data acquisition and processing
  - Motor control and movement logic
  - Gripper actuation based on detection triggers
  - Safety and boundary checks

