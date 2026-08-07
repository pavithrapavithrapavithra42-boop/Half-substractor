# Half Subtractor using Verilog HDL

## Overview

A Half Subtractor is a combinational logic circuit that subtracts one binary bit (B) from another binary bit (A). It produces two outputs:

- Difference (D)
- Borrow (Bout)

## Inputs

- A (Minuend)
- B (Subtrahend)

## Outputs

- Difference
- Borrow

## Boolean Expressions

Difference = A ^ B

Borrow = ~A & B

## Truth Table

| A | B | Difference | Borrow |
|---|---|------------|--------|
| 0 | 0 |     0      |   0    |
| 0 | 1 |     1      |   1    |
| 1 | 0 |     1      |   0    |
| 1 | 1 |     0      |   0    |

## Project Files

| File | Description |
|------|-------------|
| half_subtractor.v | Verilog design |
| half_subtractor_tb.v | Testbench |
| simulation_output.png | Simulation waveform |
| README.md | Project documentation |

## Software Used

- Verilog HDL
- ModelSim / Vivado / Xilinx ISE

## How to Run

1. Compile `half_subtractor.v`.
2. Compile `half_subtractor_tb.v`.
3. Run the simulation.
4. Observe the waveform and verify the outputs.

## Expected Output

The simulation tests all four possible input combinations and verifies the Difference and Borrow outputs.

## Author

Your Name  
B.Tech – Electronics and Communication Engineering
