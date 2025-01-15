# Simple HW/SW Co-design of LED on Zynq

This repository contains a simple hardware/software co-design project demonstrating how to control an LED using the **Processing System (PS)** and **Programmable Logic (PL)** on a Xilinx Zynq SoC. This project serves as an introductory example for understanding and working with Zynq platforms.

## Description

In this project:
- The **Processing System (PS)** is used to initialize and control the LED.
- The **Programmable Logic (PL)** handles the hardware configuration for LED operation.

The implementation is based on two tutorial videos that explain step-by-step how to work with both the PS and PL on a Zynq SoC. 

### Reference Tutorials:
1. **Part 1**: [Introduction to PS and PL on Zynq](https://www.youtube.com/watch?v=_odNhKOZjEo)  
   Explains the basics of integrating the PS and PL in a Zynq SoC.
2. **Part 2**: [Controlling LEDs with HW/SW Co-design on Zynq](https://www.youtube.com/watch?v=AOy5l36DroY&t=0s)  
   Shows the practical implementation of controlling an LED using HW/SW co-design.




## Getting Started

### Prerequisites
To clone and run this project, ensure you have the following tools installed:
- **Vivado Design Suite** (for hardware design)
- **Vitis** (for software development)
- ZedBoard or Zynq-based FPGA platform

### Cloning the Repository
To clone the repository, run:
```bash
git clone https://github.com/rezaAdinepour/HW-SW-Co-Design.git

cd HW-SW-Co-Design 
```


### Steps of design

As explained in the video, the goal of this section is to design a Co-Design system. To achieve this, we design a simple NAND gate by:
1. Implementing an **AND** gate using the FPGA's logic blocks.
2. Designing a **NOT** module within the processing core (CPU).
3. Establishing the connections between these two designs.

It is important to note that for this exercise, we use the **EBAZ4205 board**, which features the **Zynq 7000 SoC**. This IC is recognized in the Vivado software under the part number `xc7z010clg400-3
`


An image of this board is provided in bellow:

![ebaz board](Doc/Images/ebaz_board.png)




