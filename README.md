# Linux_andgate_design-
Basic AND gate design and simulation using Verilog HDL on Linux with Icarus Verilog.
This sample  project demonstrates the design and simulation of a basic AND gate using Verilog HDL on Linux.

## Tools Used
- Verilog HDL
- Icarus Verilog
- Linux/Ubuntu

## Files
- and_gate.v
- testbench.v

## Simulation
The project was compiled and simulated using:

```bash
iverilog -o out and_gate.v testbench.v
vvp out
