# FPGA_design

Key Features

Artix-7 FPGA (XC7A35T)

Central processing and control

Supports DDR3 memory controller (Xilinx MIG)

RGMII interface to Ethernet PHY

External DDR3 SDRAM (x16)

High-speed volatile memory for data buffering

Used as a circular buffer for streaming applications

Exercises tight timing and routing constraints

Gigabit Ethernet Interface

RGMII PHY with MagJack

Supports real-time data streaming to a host PC

Intended for UDP-based streaming

QSPI Flash Configuration Memory

Stores FPGA bitstream

Supports standalone boot

Peripheral Interfaces

I²C: temperature sensor, GPIO expander

SPI: flash and expansion header

UART over USB for debug and logging

Multi-Rail Power Architecture

Dedicated rails for FPGA core, I/O, DDR3, and Ethernet PHY

Buck regulators with local decoupling

Designed with power integrity best practices