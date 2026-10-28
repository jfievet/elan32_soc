# elan32_soc
ELAN32 - Lightweight 32-bit RISC-V Processor

Designed with AI assistance

A compact, bare-metal RISC-V RV32IM processor designed for FPGA
integration. It features a multicycle architecture with registered
datapath stages to minimize combinational path delays and simplify
timing closure.

Features:
  - RV32IM instruction set
  - Multicycle, non-overlapping instruction execution
  - AXI4-Lite master interface for instructions and data
  - Hardware multiplication and division (optional)
  - Configurable reset and boot address
  - External stall and fault control
  - Register file and program counter debug interfaces

Design philosophy:
  Simplicity, low resource utilization, and predictable timing
  rather than maximum instruction throughput.
