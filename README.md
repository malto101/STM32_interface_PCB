# STM32F103C8Tx PCB Design Readme
![3d-render](https://github.com/malto101/STM32_interface_PCB/assets/70323154/f53fa15a-ef11-425d-91d1-fb6ed8d953a6)

## Overview

This readme provides an overview of the design considerations and technical details for the STM32F103C8Tx-based PCB. The PCB includes a boot switch, exposed UART and I2C pins, utilizes SWD debugging for code uploading, and is powered via USB.

## PCB Features

- **Microcontroller:** STM32F103C8Tx
- **Boot Switch:** Allows for boot mode selection
- **UART and I2C Pins:** Exposed for external communication
- **Debugging:** Utilizes SWD (Serial Wire Debug) for code uploading and debugging
- **Power:** USB powered

## Filter Capacitor Calculation

For maintaining oscillator stability, a filter capacitor (CL) is required. You've calculated the value using the formula:

CL = 2 * (CL0 - CS) = 2 * (10 - 5) pF = 10 pF

This capacitor value helps ensure reliable oscillator performance, contributing to the overall stability of your design.

## Repository Structure

- `schematic/`: The schematic diagram of your PCB design.
- `DataSheet/`: Directory showcasing component presenting the PCB.
- `tutstm32.kicad_sch`: File containing the Schematic for the PCB.
- `tutstm32.kicad_pcb`: File containing the routing of the PCB.

## Getting Started

1. Clone or download this repository to your local machine.
2. Review the schematic and PCB layout diagrams for a visual design representation.



