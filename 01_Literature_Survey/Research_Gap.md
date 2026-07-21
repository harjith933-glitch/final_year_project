# Research Gap

## 1. Background

The literature survey conducted between 2024 and 2026 identified several approaches for improving Network-on-Chip performance.

The major research directions identified include:

- Adaptive routing
- Congestion-aware routing
- Low-power NoC architectures
- Router bypassing
- Fault-tolerant routing
- Energy-efficient NoC design
- FPGA-based NoC implementations
- High-speed router architectures

---

## 2. Observed Research Directions

### Adaptive Routing

Several studies investigate adaptive routing to improve path selection and network performance.

However, adaptive routing generally requires additional hardware logic for monitoring network conditions and selecting suitable paths.

### Congestion-Aware Routing

Congestion-aware approaches attempt to avoid highly utilized network paths.

However, congestion monitoring can introduce additional hardware overhead and may increase routing decision complexity.

### Low-Power NoC

Several works investigate reducing power consumption through router architecture optimization, switching activity reduction, and turn elimination.

However, reducing power while maintaining adaptive routing performance remains a design challenge.

### FPGA-Based NoC

Several studies demonstrate NoC implementations on FPGA platforms.

However, there is scope for developing a compact and modular FPGA-oriented NoC router that combines adaptive routing, congestion monitoring, and low-power operation.

---

## 3. Identified Research Gap

Based on the surveyed literature, the following research opportunity is identified:

There is a need to investigate a practical FPGA-oriented NoC router architecture that combines:

1. Adaptive routing
2. Dynamic congestion monitoring
3. Low-power operation
4. Efficient arbitration
5. Compact hardware implementation

The challenge is to achieve improved congestion handling without introducing excessive hardware resource utilization, routing latency, or power consumption.

---

## 4. Proposed Research Direction

The proposed project focuses on:

**Adaptive Low-Power Congestion-Aware NoC Router for FPGA**

The design will investigate a 5-port NoC router architecture consisting of:

- Input FIFO buffers
- Congestion monitoring logic
- Adaptive routing unit
- Arbitration logic
- Crossbar switch
- Output ports

The congestion status of the input buffers will be considered during routing decisions.

The design will also investigate low-power techniques aimed at reducing unnecessary switching activity.

---

## 5. Expected Contribution

The proposed project aims to contribute:

- A modular 5-port NoC router architecture.
- Dynamic congestion monitoring at router level.
- Adaptive routing based on congestion conditions.
- Investigation of low-power switching reduction.
- FPGA implementation using Verilog HDL and Xilinx Vivado.
- Performance evaluation using latency, throughput, power, timing, and FPGA resource utilization.

---

## 6. Evaluation Strategy

The proposed design will be evaluated against a baseline routing implementation.

The comparison will consider:

| Metric | Evaluation |
|---|---|
| Latency | Average packet latency |
| Throughput | Packets/flits processed per cycle |
| Power | Estimated FPGA power |
| LUT Utilization | FPGA logic usage |
| Flip-Flop Utilization | Sequential resource usage |
| Maximum Frequency | Timing performance |
| Congestion Handling | Performance under congested traffic |

The final research gap and contribution will be refined after detailed analysis of the selected base paper and the complete set of verified related papers.
