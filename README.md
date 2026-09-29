# 32-Bit Pipelined Predicated RISC Processor

## Project Description

This repository contains a university project for the design and implementation of a **32-bit pipelined predicated RISC processor** using **Verilog**.

The processor supports predicated execution, where instructions are executed conditionally based on predicate register values. The design implements a five-stage pipeline to allow multiple instructions to be processed simultaneously.

## Processor Features

* 32-bit RISC processor
* 32 general-purpose registers
* Predicated instruction execution
* Separate instruction and data memories
* 14 supported instructions
* R-Type, I-Type, and J-Type instruction formats
* Five-stage pipeline architecture
* Hazard and stall management
* Forwarding unit
* Kill and stall detection
* Program Counter (PC) control
* Simulation-based verification

## Pipeline Stages

The processor uses five main pipeline stages:

1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execute (EX)
4. Memory Access (MEM)
5. Write Back (WB)

## Main Components

The project includes the design and implementation of:

* Register File
* ALU
* Instruction Memory
* Data Memory
* Control Unit
* Multiplexers
* PC Control Unit
* Forwarding Control Unit
* Kill and Stall Detection Unit
* Immediate Extension Unit
* Pipeline Buffers

## Verification

The processor was verified using simulation-based testing with custom testbenches and assembly programs.

The verification covers:

* R-Type instructions
* I-Type instructions
* Jump instructions
* CALL instructions
* Pipeline hazards
* Stall conditions
* Predicate-disabled cases
* Pipeline instruction execution
* Waveform analysis

## Technologies Used

* **Verilog HDL**
* Digital Logic Design
* RISC Architecture
* Pipelined Processor Design
* Simulation and Testbenches

## Project Report

The complete project report is provided as a PDF file and contains the processor design, implementation details, architecture, verification results, waveform analysis, and teamwork section.
