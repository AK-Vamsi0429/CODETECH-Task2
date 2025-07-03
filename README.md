Name: PARUSU KRISHNA VAMSI 
Company: CODETECH SOLUTIONS 
ID:CT06DG1294
Domain:VLSI
Duration:14June to 29 July 2025
Mentor:Neela Santosh Kumar 

🔍 Project Overview: Synchronous RAM Module
This project focuses on the development and verification of a simple synchronous RAM (Random Access Memory) module using Verilog HDL. The RAM is designed to perform read and write operations synchronously with the system clock, making it suitable for integration into larger digital systems such as CPUs, microcontrollers, or memory-mapped devices.

The memory module is parameterized to allow flexibility in data width and address width, with a default configuration of 8-bit data and 16 memory locations (4-bit address space). Read and write operations are triggered on the positive edge of the clock signal (clk).

🔧 Key Deliverables
Verilog Code
A configurable synchronous RAM module (sync_ram.v) that includes:

Memory array

Read and write control logic

Clocked process for deterministic operation

Testbench
The testbench (tb_sync_ram.v) simulates RAM behavior by applying a series of write and read operations. It uses a clock generator and $monitor to trace values over time.

Simulation
Functional simulation demonstrates proper memory operation:

Writing known data to specific addresses

Reading data back from those addresses

Verifying data integrity and timing

✅ Results Summary
Simulation results confirm that the RAM module correctly performs synchronous read and write operations. Data written to memory addresses was successfully retrieved in subsequent read cycles, validating the design’s correctness and timing behavior.
