# RISC-like Processor Simulator
Welcome to the RISC-like Processor Simulator! This project is a fun and educational implementation of a simple Reduced Instruction Set Computing (RISC) processor in C. The simulator can parse, decode, and execute instructions from a given program file, simulating a basic CPU's functionality. It includes various RISC operations such as arithmetic, logical, and branch instructions, providing a clear understanding of how a RISC processor works.

## Features
**16-bit Instruction Set:** Supports a variety of instructions including ADD, SUB, MUL, LDI, BEQZ, AND, OR, JR, SLC, SRC, LB, and SB.
**Register File:** Simulates a register file with 64 registers, each 8 bits wide.
**Instruction Memory:** Holds up to 1024 instructions.
**Data Memory:** Provides 2048 bytes of data memory.
**Status Register:** Tracks the condition flags (C, V, N, S, Z) for arithmetic operations.
**Program Counter:** Manages the flow of instruction execution.
**Instruction Decoding and Execution:** Decodes and executes instructions fetched from memory.
**Cycle Management:** The simulator advances through clock cycles, managing instruction fetch, decode, and execute stages, including handling branches.
**Pipelining:** Supports instruction pipelining to improve execution efficiency.
**Data Hazard Handling:** Detects and handles data hazards during instruction execution to ensure correct program operation.

## How It Works
**Instruction Fetch:** The program counter (PC) fetches the next instruction from instruction memory.
**Instruction Decode:** The fetched instruction is decoded to determine the operation and operands.
**Instruction Execute:** The decoded instruction is executed, updating the registers and condition flags.
**Cycle Management:** The simulator advances through clock cycles, managing instruction fetch, decode, and execute stages, including handling branches and data hazards.

## Example Usage
To run the simulator, compile and execute the main function. Ensure you have a program file named program.txt with your instructions. The simulator will fetch, decode, and execute the instructions, printing the state of the registers, condition flags, and program counter at the end of the execution.

## Sample program.txt File
A sample program.txt file is added

## Output
The simulator will output the state of the registers, condition flags, and program counter after executing the instructions. It also prints the total number of clock cycles taken to finish the execution.

## Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome!

## Contact
For any questions or suggestions, please contact me at @*georgeelswefy@gmail.com*

Enjoy exploring the world of RISC processors with this simulator! **Happy coding! 🚀**
