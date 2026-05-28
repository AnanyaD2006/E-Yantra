# FPGA-Based Maze Solver Bot | e-Yantra 2025

**Competition:** e-Yantra Robotics Competition 2025, IIT Bombay  
**Hardware:** DE0-Nano Intel FPGA

---

## Overview

An autonomous FPGA-powered robot that navigates a dynamic maze, collects environmental sensor data, and exits the maze efficiently. The entire control architecture — maze solving, sensor interfacing, and motor control — runs on the DE0-Nano Intel FPGA programmed in Verilog.

---

## Features

- **Maze solving** — autonomous navigation through a dynamic maze with real-time path decisions
- **Environmental sensing** — onboard collection of temperature, humidity (DHT11), and soil moisture data
- **UART communication** — real-time transmission of sensor data to a PC for monitoring
- **Custom PCB** — modular sensor integration with standardized electronics architecture
- **Parallel processing** — concurrent handling of sensors, motor control, and communication on FPGA fabric

---

## Hardware

| Component | Details |
|-----------|---------|
| FPGA Board | DE0-Nano (Intel Cyclone IV) |
| Temperature & Humidity | DHT11 sensor |
| Soil Moisture | Analog soil moisture sensor |
| Communication | UART to PC |
| PCB | Custom-designed for sensor integration |

---

## Tools

- **Verilog** — RTL design and hardware description
- **Intel Quartus Prime** — synthesis and place and route
- **ModelSim** — simulation and functional verification
