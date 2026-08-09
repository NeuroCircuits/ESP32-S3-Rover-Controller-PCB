# ESP32-S3-Rover-Controller-PCB
Custom ESP32-S3 based controller PCB for a 6-wheel robotic platform, featuring servo control, DC motor drivers, IMU, RFID, USB programming, and dedicated power regulation.

## Overview

This project is a custom controller PCB designed for a mobile robotic platform.

The board is built around the ESP32-S3-WROOM-1U and integrates the main electronics required for controlling the robot, reducing the need for separate wiring and controller boards.

The PCB was designed from schematic to final PCB layout in KiCad, including routing, power distribution, grounding, mounting holes, design-rule checking, and Gerber generation.

## Features

- ESP32-S3-WROOM-1U main controller
- USB Type-C programming interface
- USB-to-UART interface
- Automatic programming / reset circuitry
- PCA9685 16-channel PWM controller
- Support for multiple high-torque servos
- Interfaces for 4 × BTS motor-driver modules
- Control for 6 DC motors
- MPU6050 IMU interface
- RC522 RFID interface
- 3.3 V regulated supply for logic
- 5 V regulated supply
- Dedicated 6 V servo power rail
- High-current power input
- Main power switching
- Fuse protection
- Multiple bulk and decoupling capacitors
- Through-hole mounting holes
- Two-layer PCB
- Custom copper power and GND planes

- ## PCB Design

Designed using KiCad.

The design includes:

- Schematic capture
- Component selection and footprint assignment
- PCB layout
- Power and ground distribution
- Signal routing
- Copper zones
- Mounting holes
- Silkscreen labeling
- Design Rule Check (DRC)
- Gerber generation
