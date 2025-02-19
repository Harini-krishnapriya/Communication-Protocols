# System Verilog for verification
Welcome to the System verilog Repository! This repository aims to provide a comprehensive collection of various System verilog Concepts.

## Table of Contents

- [Fundamentals of Design Verification](#Fundamentals-of-Design-Verification)
- [SystemVerilog Interfaces](#SystemVerilog-Interface)

  
## Fundamentals of Design Verification

There are three types of signals in a design. They are:
1. Global signals: Signals that are visiable to the entire design,e.g CLK, RST signals.
2. Data signals: Signals that hold some data, e.g rdata, wdata
3. Control signals: Signals that control various operations.

## SystemVerilog Interfaces
1. Verilog has low level of abstraction for communication between modules.
2. it hsa limited reusability.
3. Verilog DUTs are static modules which can't be connected with SV TBs through ports.
4. Interface is a Static Component
5. It Encapsulated communication between hardware blocks
6. Bundle of signals
7. Interfaces can be used for both DUT and TB components
8. Supports always, initial, task, function, assertion, covergroup
9. Virtual Interfaces - used to connect the VErilog DUTs and SV TBs
