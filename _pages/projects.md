---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

* Design and Tapeout of CORDIC module with TSMC 65nm Process Node 
RTL Design of COordinate Rotation DIgital Computer module. Carried out Synthesis, APR and verified 
compliance with target specifications at each stage. Post-Silicon Validation of taped-out chip using Scan chain 
tests controlled by Raspberry Pi. [System Verilog / Tcl] (Sponsored by Apple in collaboration with Georgia Tech) 

* Integration of Streaming Buffer into Vortex GPGPU Architecture 
RTL implementation of a BRAM-based MMIO-accessible streaming buffer integrated into Vortex GPGPU. 
Designed address decoding and AXI-based routing logic for core-to-buffer communication. Verified functionality 
on U50 FPGA using Xilinx XRT simulation. [System Verilog] (Research under Prof. Hyesoon Kim at Georgia Tech) 

* Performance Evaluation of 5-stage Pipelined Superscalar architecture 
Created hazard detection unit which supports stalling for RAW hazards and forwarding of data across the 
pipelines; Integrated Always-Taken and G-Share Branch Predictors. Further, incorporated Tomasulo algorithm 
to implement Out-Of-Order execution by employing register renaming & Reorder Buffer strategy. [C++]

* Multi-Level Cache and Memory System Design Simulator
Developed and optimized a multi-level cache simulator with configurable cache sizes and replacement policies. 
Modeled DRAM memory with open and close page policies, improving memory access latency and performance. 
Tested and benchmarked against SPEC2006 benchmarks to evaluate cache performance. [C++] 

* RTL Design of Ethernet address swapping module and testing using System Verilog 
Designed a module for swapping source and destination addresses in ethernet packets. Developed a System 
Verilog-based test bench environment for verifying the functional correctness of the block using constrained 
random verification on the ModelSim tool. [System Verilog] 

* RTL implementation of Error Correction Techniques: Convolution Encoder with Viterbi 
Decoder and LDPC Encoder with bit-flipping algorithm 
Designed encoder/decoder for each of the above techniques and verified functionality on Vivado (Xilinx) 
simulator. Comparative study was made in terms of Power, Area and Resource usage. [Verilog] 

* GPU Warp Scheduling and Compute Core Simulation 
Implemented GPU simulator with advanced warp scheduling algorithms (RR, GTO, CCWS) and modeled 
compute / tensor core pipelines with realistic latency and dependency handling. Analyzed performance trade-offs 
across varying tensor latencies and execution widths using benchmark traces. [C++] 

* GPU-Accelerated Bitonic Sort using CUDA 
Developed and optimized a parallel Bitonic sort on NVIDIA H100 using shared memory tiling, coarsened 
merging, and multi-stream transfers. Achieved ~147x CPU speedup, 90% occupancy, and ~ 800M elements/sec 
throughput through memory coalescing and kernel tuning. [CUDA] 

* SRAM Design, Layout, Extraction and Simulation  
Creation of SRAM peripherals (Decoder Logic, WL generation, Column MUX); Design of SRAM cell, array, 
read / write circuit; Layout of the design and timing from the extracted circuit. [Cadence] 

* Collective Communication Optimization using MSCC-Lang on Hierarchical Mesh Topologies 
Implemented and optimized hierarchical all-reduce collectives using MSCC-Lang. Designed multi-phase 
communication patterns on 2D mesh topologies and validated performance using XML generation. Focused on 
ring-based collective strategies with buffer management and chunk indexing. [Python] 
