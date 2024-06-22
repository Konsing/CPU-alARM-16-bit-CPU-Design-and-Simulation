### README.md

```markdown
# CPU alARM: 16-bit CPU Design and Simulation

This repository contains the files and documentation for the design and simulation of a 16-bit CPU called alARM. The project involves building the CPU using Logisim and testing it with various assembly instructions.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Instruction Set](#instruction-set)
- [Circuit Descriptions](#circuit-descriptions)

## Introduction
This project demonstrates the implementation and simulation of a 16-bit CPU named alARM. The CPU supports various operations including data movement, arithmetic and logic operations, and branching.

## Project Structure
The project includes the following files:
- **Lab3 Write Up.pdf**: Detailed documentation of the project, including instruction sets and implementation details.
- **Lab3a1037.circ**: Logisim circuit file for the CPU design.
- **Display4242.hex**: Hexadecimal file for testing display functionality.
- **fibo.hex**: Hexadecimal file for running the Fibonacci sequence.
- **GivenCode.hex**: Sample hexadecimal code for various CPU operations.

## Getting Started

### Prerequisites
- Logisim software, which can be downloaded from [Logisim's official website](http://www.cburch.com/logisim/).
- A text editor for viewing `.hex` files.

### Installation
1. Download and install Logisim from the [official website](http://www.cburch.com/logisim/).
2. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/cpu-alarm.git
   cd cpu-alarm
   ```

## Usage
1. Open Logisim.
2. Open the `Lab3a1037.circ` file in Logisim.
3. Load any of the provided `.hex` files into the memory of the CPU for simulation.
4. Run the simulation by interacting with the components in Logisim.

## Instruction Set
The CPU supports the following instructions:
- **MOV**: Move immediate or register value.
- **ADD**: Add values.
- **SUB**: Subtract values.
- **MUL**: Multiply values.
- **DIV**: Divide values.
- **MOD**: Modulus operation.
- **AND**: Bitwise AND.
- **OR**: Bitwise OR.
- **EOR**: Bitwise XOR.
- **NOT**: Bitwise NOT.
- **LSL**: Logical shift left.
- **LSR**: Logical shift right.
- **ASR**: Arithmetic shift right.
- **ROL**: Rotate left.
- **ROR**: Rotate right.
- **CMP**: Compare values.
- **B**: Unconditional branch.
- **BEQ**: Branch if equal.
- **BNE**: Branch if not equal.

## Circuit Descriptions

### Lab3a1037.circ
This file contains the Logisim implementation of the 16-bit alARM CPU. It includes the following components:
- **ALU (Arithmetic Logic Unit)**: Performs all arithmetic and logic operations.
- **Register File**: Holds the CPU registers.
- **Instruction Fetch Unit**: Fetches instructions from memory.
- **Decoder Controller**: Decodes instructions and controls the operation of the CPU.
- **Data Memory**: Stores data and instructions.
- **Decimal Display Control**: Handles the display of decimal numbers using the Double Dabble algorithm.