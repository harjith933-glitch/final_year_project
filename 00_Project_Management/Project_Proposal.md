# Project Proposal

## Project Title

**Adaptive Low-Power Congestion-Aware NoC Router for FPGA**

## Project Domain

VLSI Design and FPGA-Based Digital System Design

## Project Overview

Network-on-Chip (NoC) architectures are widely used for communication between multiple processing elements in modern System-on-Chip (SoC) designs. As the number of processing elements increases, communication congestion, packet latency, power consumption, and resource utilization become important design challenges.

This project focuses on the design and implementation of an adaptive low-power congestion-aware NoC router using Verilog HDL. The proposed router monitors congestion conditions at its input buffers and dynamically selects suitable routing paths to improve communication performance.

The design will be developed at RTL level and functionally verified using simulation. The complete design will then be synthesized and implemented on an FPGA using Xilinx Vivado.

## Problem Statement

Conventional NoC routers may use fixed routing decisions that do not consider the current congestion conditions of the network. This can lead to increased packet latency, reduced throughput, and unnecessary switching activity.

Therefore, there is a need for an adaptive NoC router capable of considering congestion conditions while making routing decisions and reducing unnecessary hardware activity.

## Proposed Solution

The proposed project develops a 5-port NoC router with:

- Input FIFO buffers
- Congestion monitoring
- Adaptive routing
- Arbitration logic
- Crossbar switching
- Low-power design techniques

The router will dynamically select routing paths based on the congestion status of available output directions.

## Expected Outcome

The expected outcome is a functional FPGA-based NoC router capable of:

- Adaptive congestion-aware packet routing
- Improved packet flow under network congestion
- Reduced unnecessary switching activity
- Efficient resource utilization
- Reliable packet communication

## Tools

- Verilog HDL
- Xilinx Vivado
- FPGA Development Board
- GitHub

## Project Deliverables

1. Literature survey
2. System architecture
3. RTL design
4. Functional verification
5. FPGA synthesis
6. Timing analysis
7. Power analysis
8. Resource utilization analysis
9. Performance evaluation
10. IEEE-style research paper
