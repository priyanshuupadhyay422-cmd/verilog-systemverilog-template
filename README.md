# Verilog & SystemVerilog Template Library

**A practical collection of reusable HDL examples for digital design, RTL development, FPGA engineering, and hardware verification.**

Explore fundamental digital circuits and advanced SystemVerilog concepts through organized code examples and detailed explanations.

## Overview

The **Verilog & SystemVerilog Template Library** is a learning resource for students, aspiring RTL designers, FPGA engineers, and VLSI enthusiasts. It provides reusable hardware description language examples to help users understand digital logic, sequential circuits, RTL coding practices, and verification concepts.

Whether you are learning Verilog for the first time or strengthening your SystemVerilog fundamentals, this repository serves as a reference for studying, experimenting with, and building upon HDL designs.

## Key Features

- **Reusable HDL code:** Organized examples for common digital design tasks.
- **Digital logic fundamentals:** Gates, arithmetic circuits, multiplexers, decoders, and encoders.
- **Sequential circuit design:** Flip-flops, registers, counters, and shift registers.
- **RTL design concepts:** ALUs, finite state machines, memories, and FIFOs.
- **SystemVerilog features:** Arrays, data types, tasks, functions, classes, and packages.
- **Verification concepts:** Constrained randomization, mailboxes, semaphores, and interfaces.
- **Learning-oriented documentation:** Explanations, code examples, and expected behavior where provided.

## Topics Covered

| Category | Examples |
|---|---|
| Combinational Logic | Logic gates, adders, subtractors, multiplexers, decoders |
| Arithmetic & Data Processing | ALUs, comparators, parity circuits, Gray code converters |
| Sequential Logic | Latches, flip-flops, registers, counters |
| Shift & Sequence Circuits | Shift registers, ring counters, Johnson counters, LFSRs |
| Finite State Machines | Moore and Mealy sequence detectors |
| RTL Coding | `always_comb`, `always_ff`, enumerated FSMs |
| Memory Design | RAM, synchronous FIFO |
| SystemVerilog Data Structures | Packed arrays, unpacked arrays, dynamic arrays, queues, associative arrays |
| Object-Oriented Programming | Classes, objects, inheritance, polymorphism |
| Verification | Constrained randomization, mailboxes, semaphores |
| Reusable Design Structures | Interfaces, modports, packages, tasks, functions |

## Repository Structure

```text
verilog-systemverilog-template121/
├── verilog/          # Verilog HDL source files (.v)
├── system_verilog/   # SystemVerilog source files (.sv)
├── explanation/      # Markdown documentation and examples
├── website/          # Browser-based template library, if included
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/priyanshuupadhyay-cmd/verilog-systemverilog-template121.git
cd verilog-systemverilog-template121
```

### 2. Explore the Templates

Browse the source files in `verilog/` and `system_verilog/`. Consult `explanation/` for corresponding documentation when available.

### 3. Compile and Simulate

You can use tools such as:

- **Icarus Verilog** — command-line compilation and simulation.
- **GTKWave** — waveform inspection.
- **AMD Vivado** — FPGA design, synthesis, and simulation.
- **Verilator** — HDL linting and supported simulation workflows.
- **QuestaSim / ModelSim** — HDL simulation and debugging.

For example, to compile and simulate a Verilog module with Icarus Verilog:

```bash
iverilog -o simulation.out verilog/your_module.v verilog/your_testbench.v
vvp simulation.out
```

Replace the example filenames with the actual source and testbench filenames. If a template uses SystemVerilog features, compile it with the appropriate SystemVerilog option, such as `-g2012`, and include all required source files.

## How to Use This Repository

1. Choose a topic you want to learn.
2. Read the corresponding explanation, if available.
3. Review the HDL implementation.
4. Create or adapt a testbench to verify the design.
5. Simulate the circuit and inspect its behavior.
6. Modify the implementation and experiment with different inputs or parameters.

**Learning tip:** Focus on understanding why the circuit works, not just copying the code. Check reset behavior, timing, boundary conditions, and synthesis compatibility where applicable.

## Who Is This For?

- Electronics and communication engineering students
- Beginners learning Verilog and SystemVerilog
- FPGA development enthusiasts
- Aspiring RTL design and verification engineers
- VLSI students preparing for technical interviews
- Developers building a personal HDL reference library

## Tools and Technologies

`Verilog` · `SystemVerilog` · `Icarus Verilog` · `GTKWave` · `AMD Vivado` · `Verilator` · `QuestaSim`

Tool compatibility depends on the language constructs used in each example.

## Contributions

Contributions that improve the library are welcome.

You can contribute by:

- Adding useful Verilog or SystemVerilog templates.
- Improving documentation and code comments.
- Adding testbenches and simulation instructions.
- Fixing bugs or improving coding style.
- Suggesting new digital design or verification topics.

Please keep examples readable, use descriptive filenames, and include clear explanations where possible.

## License

No license is currently specified. Please check the repository for an applicable license before redistributing or reusing its contents.

## Author

**Priyanshu Upadhyay**

Electronics & Communication Engineering | Digital Design | Verilog & SystemVerilog | FPGA | VLSI

---

If this repository helps you learn or practice HDL design, consider starring it on GitHub and sharing it with other learners.

**Learn the logic. Write the RTL. Verify the design. Build your hardware skills.**
