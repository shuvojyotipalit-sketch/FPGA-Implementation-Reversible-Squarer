# FPGA-Implementation-Reversible-Squarer
Efficient 4×4 squarer circuit using reversible logic, implemented in Verilog and deployed on Artix-7 FPGA with optimized quantum cost, delay, and power.
# Overview

This project presents the design and FPGA implementation of a 4×4 squarer circuit using reversible logic techniques. The goal is to achieve high-speed and low-power computation by minimizing quantum cost, delay, and hardware complexity.

# Key Features
Designed using Verilog HDL
Implemented on Artix-7 FPGA (Nexys A7 board)
Utilizes Peres Gate (PG) and Hybrid New Gate (HNG)
Optimized for:
Reduced quantum cost
Lower garbage outputs
Minimal Total Reversible Logic Implementation Cost (TRLIC)
# Performance Highlights
# Delay: 1.076 ns
# Static Power Consumption: 0.136 W
# Quantum Cost Reduction: 84.34%
# TRLIC Reduction: 82.10%
# Only 12 reversible gates used

(These improvements are validated through simulation and FPGA testing in the paper.)

# Design Methodology
Partial Product Generation:
Implemented using Peres gates with ancilla inputs
Summation Stage:
Uses reversible full adders (HNG gate) and half adders
Carry Save Technique applied for efficient summation

(Page 2–3 diagrams show the block-level architecture and gate design.)

# Simulation & Validation
Simulated using Xilinx Vivado & ISE 14.7
Verified with multiple test cases (see Table on page 3)
RTL design and waveform outputs confirm correctness
FPGA implementation matches simulation results
# Applications
Quantum computing circuits
Low-power VLSI systems
High-speed arithmetic units
Energy-efficient digital design
# Conclusion

The proposed reversible logic-based squarer circuit significantly improves speed, efficiency, and scalability over traditional designs. It demonstrates strong potential for future low-power and high-performance digital systems.
