# STM32F103C8Tx PCB Design Readme

## Overview

This readme provides an overview of the design considerations and technical details for the STM32F103C8Tx-based PCB you've created. The PCB includes a boot switch, exposed UART and I2C pins, utilizes SWD debugging for code uploading, and is powered via USB.

## PCB Features

- **Microcontroller:** STM32F103C8Tx
- **Boot Switch:** Allows for boot mode selection
- **UART and I2C Pins:** Exposed for external communication
- **Debugging:** Utilizes SWD (Serial Wire Debug) for code uploading and debugging
- **Power:** USB powered
- **Filter Capacitor:** Filter capacitor calculation for oscillator stability

## Filter Capacitor Calculation

For maintaining oscillator stability, a filter capacitor (CL) is required. You've calculated the value using the formula:

CL = 2 * (CL0 - CS) = 2 * (10 - 5) pF = 10 pF

This capacitor value helps ensure reliable oscillator performance, contributing to the overall stability of your design.

## Repository Structure

- `schematic/`: The schematic diagram of your PCB design.
- `pcb_layout.pdf`: The PCB layout diagram showcasing component placement.
- `source_code`: Directory containing the source code for your microcontroller.
- `design_files`: Directory with additional design-related files, such as the Bill of Materials (BOM) and Gerber files for manufacturing.

## Getting Started

1. Clone or download this repository to your local machine.
2. Review the schematic and PCB layout diagrams for a visual design representation.



