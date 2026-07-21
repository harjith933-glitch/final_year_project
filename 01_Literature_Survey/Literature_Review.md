# Literature Review

## 1. Introduction

Network-on-Chip (NoC) architectures have become an important communication infrastructure for modern System-on-Chip (SoC) designs. As the number of processing elements increases, traditional shared-bus architectures face limitations related to scalability, communication bandwidth, latency, and power consumption.

NoC architectures address these challenges by providing packet-based communication through interconnected routers and links.

The performance and efficiency of an NoC are strongly influenced by the router architecture, routing algorithm, congestion management strategy, power consumption, and network topology.

This literature survey studies recent developments in these areas, with emphasis on research published between 2024 and 2026.

---

## 2. NoC Router Architecture

Several studies have investigated improvements in NoC router architecture and network topology.

The paper "Ring Road: A Scalable Polar-Coordinate-based 2D Network-on-Chip Architecture" investigates a scalable NoC topology using isolated multi-ring channels and compact routers.

The study demonstrates improvements in bandwidth-per-area and bandwidth-per-power compared with conventional mesh-based routers.

The paper "Two-level Routerless Network-on-Chip" investigates a routerless NoC architecture using horizontal and vertical loops to provide path diversity.

Another work, "Design and Analysis of a 5-Port Router with Enhanced Features for NoC Applications", investigates a 5-port router with QoS support and priority-based arbitration using Verilog HDL.

These studies demonstrate that router architecture and network topology significantly influence NoC performance and hardware efficiency.

---

## 3. Adaptive Routing

Adaptive routing allows a router to dynamically select a path based on network conditions.

The literature includes studies on adaptive routing for different NoC architectures, including fault-tolerant and secure routing.

"Securet3d: An Adaptive, Secure, and Fault-Tolerant Aware Routing Algorithm for Vertically-Partially Connected 3D-NoC" investigates adaptive routing while considering security and fault tolerance.

"Fault-Tolerant Adaptive Routing Algorithm for Mesh Network Based on the Turn Model" investigates adaptive routing for mesh NoCs while maintaining fault tolerance and avoiding deadlock conditions.

These works demonstrate the importance of adaptive routing in improving network reliability and communication performance.

---

## 4. Congestion-Aware Routing

Congestion is a major factor affecting NoC performance.

The paper "Low Congestion-Based Routing Algorithm in Optical Network-on-chip" investigates a congestion-avoiding routing strategy for optical NoCs.

The approach aims to reduce congestion-related communication problems and improve end-to-end performance.

The study "A Study on Proactive Adaptation-Based Routing Strategies in 2D Network-on-Chip Architectures" analyzes proactive adaptation strategies that anticipate congestion and reliability conditions.

These studies indicate that routing decisions based on traffic and congestion conditions can potentially improve network performance compared with fixed routing approaches.

---

## 5. Low-Power NoC Design

Power consumption is an important design concern in modern NoC-based systems.

The paper "Tulip: Turn-Free Low-Power Network-on-Chip" investigates a turn-free NoC architecture that reduces router complexity and power consumption.

The paper "Low Power Network-on-Chip Architecture Design Technique" investigates techniques for reducing switching activity and dynamic power consumption.

The literature demonstrates that reducing unnecessary switching activity and optimizing router architecture can contribute to lower NoC power consumption.

---

## 6. Energy-Efficient NoC Design

Energy efficiency can also be improved through intelligent task mapping and communication optimization.

"Enhancing Reliability and Energy Efficiency in NoC Architectures through Hybrid Sorting Algorithm-Based Core Mapping" investigates core mapping techniques to reduce communication overhead and energy consumption.

"Enhancing Reliability and Energy Efficiency in Many-Core Processors Through Fault-Tolerant Network-on-Chip" investigates energy-aware task mapping and fault-tolerant NoC communication.

These works demonstrate the relationship between communication patterns, task mapping, reliability, and NoC energy efficiency.

---

## 7. FPGA-Based NoC Implementation

FPGA implementation provides a practical platform for evaluating NoC architectures.

"A 100Gbps-ready Low Latency on-Chip Router for FPGA clusters" investigates a high-bandwidth on-chip router architecture targeting FPGA clusters.

The study demonstrates the feasibility of implementing high-speed router architectures on modern FPGA platforms.

"Network on Chip (NoC) Mesh Topology FPGA Verification: RTOS Emulation Framework" investigates FPGA-based verification of a mesh NoC using traffic models and an RTOS-managed communication environment.

These studies highlight the importance of FPGA-based implementation and verification for evaluating NoC designs.

---

## 8. Fault-Tolerant and Reliable NoC

Reliability is an important consideration in large-scale NoC systems.

The literature includes fault-tolerant routing and energy-aware mapping techniques that aim to maintain network performance in the presence of failures.

Adaptive and fault-aware routing approaches can improve network reliability by avoiding faulty or unavailable paths.

However, additional fault detection and routing logic can increase hardware complexity.

---

## 9. Intelligent NoC Architectures

Recent research has also investigated intelligent and AI/ML-based approaches for NoC routing and optimization.

The systematic review "Latest Innovations in Intelligent Network-on-Chip Architectures" examines recent developments involving intelligent techniques for NoC routing, latency optimization, power management, and security.

Although intelligent approaches provide promising opportunities, they may introduce additional computational and hardware overhead.

For an FPGA-oriented project with limited implementation time and resources, a hardware-based congestion-aware adaptive routing mechanism provides a more practical direction.

---

## 10. Buffer and Router Optimization

The paper "BuffeRS: A Buffer Reservation Scheduling Strategy for Router Bypassing in NoCs and Multichiplet Networks" investigates buffer reservation scheduling and router bypassing.

The approach attempts to improve packet delivery by dynamically configuring bypass paths and coordinating router operation.

This work demonstrates the importance of optimizing buffer utilization and router data paths for improving NoC performance.

---

## 11. Summary of Literature

The surveyed literature demonstrates that NoC performance can be improved through:

- Adaptive routing
- Congestion-aware routing
- Low-power techniques
- Router architecture optimization
- Buffer optimization
- Fault-tolerant routing
- FPGA-oriented implementations
- Efficient arbitration
- Improved network topologies

However, these techniques often focus on individual optimization objectives.

The proposed project aims to investigate the combined design of an adaptive routing mechanism with congestion monitoring and low-power operation in a 5-port FPGA-oriented NoC router.

The project will evaluate the resulting design in terms of:

- Packet latency
- Throughput
- Power consumption
- FPGA resource utilization
- Maximum operating frequency
- Routing behavior under congestion
