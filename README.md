# Mini-SoC RTL Simulation

A beginner-friendly Mini-SoC project that integrates a 4-bit synchronous counter, a 2-bit ALU, and a 2:1 multiplexer using Verilog RTL.

## Project Overview

This project demonstrates basic RTL design and IP integration. The counter generates data, the ALU performs addition or subtraction, and the multiplexer selects the final output.

## Modules

- counter.v — 4-bit synchronous up counter with synchronous reset
- alu.v — 2-bit addition/subtraction ALU
- mux2x1.v — 2-bit 2:1 multiplexer
- mini_soc.v — Top-level Mini-SoC integrating the modules
- mini_soc_tb.v — Testbench for simulation
- run.sh — Verilator simulation script

## Tools Used

- Verilog HDL
- Verilator
- GTKWave
- Git & GitHub

## How to Run

Make the script executable:

```bash
chmod +x run.sh
```

Run the simulation:

```bash
./run.sh
```

The simulation generates a VCD waveform that can be viewed using GTKWave.

## Simulation Flow

Verilog RTL → Verilator → Simulation → VCD Waveform → GTKWave

## Learning Outcome

This project provides hands-on practice with modular RTL design, module instantiation, testbench creation, Verilator-based simulation, waveform analysis, and basic GitHub project management.
