# FPGA Digital Logic

A collection of FPGA-based digital logic designs developed using Intel/Altera Quartus Prime and the Intel MAX 10 platform.

This repository documents combinational and sequential logic circuits through schematic design, compilation, simulation, and functional verification. The projects originated from digital-logic coursework and have been independently reorganized, recompiled, revalidated, and documented for this engineering portfolio.

## Hardware and Software

- Intel/Altera Quartus Prime Lite
- Intel MAX 10 FPGA
- DE10-Lite development board
- Quartus Block Diagram/Schematic Editor
- Quartus Simulation Waveform Editor
- ModelSim/Questa simulation workflow

## Projects

### 1-Bit Full Adder

A combinational logic circuit that adds three 1-bit binary inputs and produces `SUM` and `CARRY` outputs.

The design was successfully recompiled in Quartus Prime Lite 25.1 and functionally verified across all eight possible input combinations.

[View the 1-Bit Full Adder](1-bit-full-adder/)

### 4-Bit Ripple-Carry Full Adder

A 4-bit binary adder constructed by cascading four reusable 1-bit full-adder blocks.

The design accepts two 4-bit operands and an external carry-in, producing a 4-bit sum and final carry-out. It was successfully recompiled in Quartus Prime Lite 25.1 and functionally verified through representative addition and carry-propagation test cases.

[View the 4-Bit Full Adder](4-bit-full-adder/)

More FPGA projects will be added as they are reconstructed, verified, and documented.

## Planned Projects

- NAND-Based D Flip-Flop
- Boolean-Minimized Logic Circuit
- Seven-Segment Decoder
- Binary Counter

## Verification Approach

Each published design is checked through a combination of:

1. Quartus compilation
2. Functional simulation
3. Expected truth-table or state behavior
4. Visual inspection of simulation results
5. Hardware verification where applicable

Only designs that have been successfully reconstructed and verified are presented as completed projects.

## Repository Structure

```text
fpga-digital-logic/
├── README.md
├── 1-bit-full-adder/
│   ├── README.md
│   ├── Fulladder1bitNO.bdf
│   ├── Fulladder1bitNO.qpf
│   ├── Fulladder1bitNO.qsf
│   ├── Waveform.vwf
│   └── images/
├── 4-bit-full-adder/
├── nand-d-flip-flop/
├── boolean-minimization/
├── seven-segment-decoder/
└── counter/

```

## Portfolio

Additional engineering projects are available at:

**https://nortiz01.github.io**
