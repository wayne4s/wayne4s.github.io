---
layout: single
title:  "Blog @ simulators"
permalink: /blogs/simulators
---

## Multicore Architecture Simulators

### McPAT

- [2009 MICRO] McPAT: An Integrated Power, Area, and Timing Modeling Framework for Multicore and Manycore Architectures. [![](https://img.shields.io/badge/paper-7EA6E0)](https://perso.ens-lyon.fr/christophe.alias/evalM2/micro09b.pdf) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/HewlettPackard/mcpat)

McPAT enables architects to consistently quantify the cost of new ideas and
assess tradeoffs of different architectures using new metrics like energy-delay-area<sup>2</sup> product (EDA<sup>2</sup>P) and energy-delayarea product (EDAP).
It can model the area and power of the register files and the SRAM buffers.


### ZSim

- [2013 ISCA] ZSim: Fast and Accurate Microarchitectural Simulation of Thousand-core Systems. [![](https://img.shields.io/badge/paper-7EA6E0)](https://people.csail.mit.edu/sanchez/papers/2013.zsim.isca.pdf) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/s5z/zsim)

zsim is a fast x86-64 simulator, and its main goals are to be fast, simple, and accurate, with a focus on simulating memory hierarchies and large, heterogeneous systems. 

## Memory Simulators

### DRAMSim3

- DRAMsim3: a Cycle-accurate, Thermal-Capable DRAM Simulator. [![](https://img.shields.io/badge/paper-7EA6E0)](https://par.nsf.gov/servlets/purl/10216399) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/umd-memsys/DRAMsim3)

DRAMsim3 models the timing paramaters and memory controller behavior for several DRAM protocols such as DDR3, DDR4, LPDDR3, LPDDR4, GDDR5, GDDR6, HBM, HMC, STT-MRAM. It is implemented in C++ as an objected oriented model that includes a parameterized DRAM bank model, DRAM controllers, command queues and system-level interfaces to interact with a CPU simulator (GEM5, ZSim) or trace workloads. It is designed to be accurate, portable and parallel.

### Mess

- [2024 MICRO] A Mess of Memory System Benchmarking, Simulation and Application Profiling. [![](https://img.shields.io/badge/code-B5739D)](https://github.com/bsc-mem/Mess-simulator)


## DNN simulators

- Scale-sim
- Timeloop



