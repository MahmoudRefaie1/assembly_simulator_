
# RISC-V Simulator

This repository contains a simple RISC-V simulator implemented in C++. The simulator supports basic arithmetic, logical, load, store, and control flow instructions for the RISC-V architecture. It also includes an assembler to convert assembly code into machine code. The program simulates the execution of RISC-V programs and displays the state of registers, memory, and program counter during execution.

## Features

- **Basic Arithmetic Operations**: ADD, SUB, AND, OR
- **Immediate Arithmetic Operations**: ADDI, SUBI
- **Load/Store Operations**: LW, SW
- **Branch Instructions**: BEQ, BNE
- **Jump Instructions**: JAL
- **Program Counter Management**
- **Display State**: View register values (in decimal, binary, and hexadecimal formats)
- **Display Memory**: View memory contents (in decimal, binary, and hexadecimal formats)
- **Test Cases**: Several test cases with assembly programs and data files

## Instructions

### Compilation and Execution

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/riscv-simulator.git
   cd riscv-simulator
   ```

2. **Compile the code**:
   Using `g++` or any C++ compiler:
   ```bash
   g++ -o riscv_simulator simulator.cpp
   ```

3. **Run the simulation**:
   ```bash
   ./riscv_simulator
   ```

### Directory Structure

- `tests/programs/`: Contains test case program files (assembly code).
- `tests/data/`: Contains test case data files (initial memory and register values).
- `simulator.cpp`: The main C++ code for the simulator.
- `README.md`: This file.

### Example Test Cases

The test cases are provided in the `tests` directory and include various RISC-V instructions, including arithmetic, load/store, and control flow operations. For each test case, a program file and a data file are provided. The simulator will load these files, run the instructions, and display the results.

## Authors

- Mahmoud Refaie
- Nadine Elgarem
- Hamza Abbas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This **README.md** focuses on:
1. A **description** of the project and its features.
2. **Compilation and execution** instructions.
3. **Directory structure** to help users navigate the project.
4. **Test case usage** and how to run them.
5. The **authors** and **license** information.

This should now be correctly formatted for your GitHub repository!
