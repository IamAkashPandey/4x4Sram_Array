# 4x4Sram_Array
4x4 SRAM Array Design
Project Overview
This project involves the design and simulation of a 4x4 SRAM array. The Static Random Access Memory (SRAM) is designed using 6T (six-transistor) cells along with peripheral circuits such as a sense amplifier, write driver, pre-charge circuit, row decoder, and column multiplexer. The project demonstrates the basic operations of an SRAM array including read and write operations, along with delay and stability analysis.

Presented by: Akash Pandey (2302102035)
Lab: NSDCS Lab, Department of Electrical Engineering, IIT Indore
Lab In-Charge: Prof. Santosh Kumar Vishvakarma
Components of the SRAM Array
Basic Building Blocks:
6T SRAM Cell: Each cell stores a single bit of data. The 6T configuration offers a balance between speed, power, and stability.
Sense Amplifier: Used to read data from the bit lines during a read operation.
Write Driver: Drives the data onto the bit lines during a write operation.
Pre-charge Circuit: Prepares the bit lines before a read or write operation to ensure accurate data transmission.
Row Decoder (2:4 Decoder): Decodes the 2-bit input to select one of the four rows for accessing the memory.
Column Multiplexer (Column Mux): Allows selecting a specific column from the memory array during read/write operations.
Schematic and Layouts:
6T SRAM Cell Schematic & Layout: Shows the transistor-level configuration of the SRAM cell.
Latch-Based Sense Amplifier: A schematic showing the design of a sense amplifier used for read operations.
Write Driver Schematic: Shows the configuration used for driving the write data.
Pre-Charge Circuit: A schematic of the circuit responsible for pre-charging the bit lines.
2:4 Decoder and Column Mux: Essential for selecting rows and columns during operations.
4x4 SRAM Array:
The complete 4x4 SRAM array consists of 16 SRAM cells (4 rows and 4 columns). Operations include reading and writing data into specific rows and columns. For instance, writing data 1001 to Row 1 is a core example used in the project.

Key Operations
Read Operation:

During a read operation, the pre-charged bit lines are used, and the sense amplifier detects the stored data from the selected SRAM cell.
Write Operation:

In a write operation, the write driver writes data to the selected SRAM cells via the bit lines, as controlled by the row and column selection.
Read/Write Delays:

The project analyzes the read and write delays of the 6T SRAM cell, helping to measure the speed and efficiency of the memory design.
SNM (Static Noise Margin) Analysis:

Read and write SNM values are plotted in MATLAB to evaluate the stability of the SRAM cells during read and write operations.
Simulations and Results
Read/Write Simulations: Various simulations are performed to verify the functionality of the read and write operations, including timing and stability analysis.
Delay Analysis: The delays in reading and writing operations are measured and evaluated.
Stability (SNM) Analysis: Read and write SNM (Static Noise Margin) is calculated to ensure the cells' reliability under various noise conditions.

Conclusion
This project successfully implements a 4x4 SRAM array using 6T SRAM cells, demonstrating fundamental read/write operations, delay analysis, and stability evaluation. The design and simulation of the SRAM array contribute to understanding the behavior and performance of SRAM in nanoscale technologies.
