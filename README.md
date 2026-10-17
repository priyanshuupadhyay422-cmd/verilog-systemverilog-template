# Verilog & SystemVerilog Templates

A collection of Verilog and SystemVerilog code templates with clear explanations, built to help beginners learn HDL programming, digital logic design, RTL design, and VLSI fundamentals. Use it for practice, quick reference, and understanding how hardware design concepts map to code.

---

## Repository Structure

```
verilog-systemverilog-template/
├── verilog/          # Verilog templates and examples
├── system_verilog/   # SystemVerilog templates and examples
├── explanation/      # Written explanations of the concepts behind the code
├── website/          # Web version of the templates and notes
└── README.md
```

| Folder | What it contains |
| --- | --- |
| `verilog/` | Ready-to-use Verilog templates for common design blocks |
| `system_verilog/` | SystemVerilog templates, including newer language constructs |
| `explanation/` | Plain-language notes explaining how and why each template works |
| `website/` | A browsable website for reading the templates and explanations |

---

## Who This Is For

- Beginners starting with HDLs and digital design
- ECE / VLSI students practicing RTL coding
- Anyone who wants a quick syntax and structure reference while writing Verilog or SystemVerilog

## What You'll Learn

- Verilog and SystemVerilog syntax and coding style
- Combinational and sequential logic
- Modules, ports, and hierarchy
- Writing RTL that is clear and synthesizable
- Basics of testbenches and simulation
- Core VLSI design fundamentals

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/priyanshuupadhyay422-cmd/verilog-systemverilog-template.git
cd verilog-systemverilog-template
```

### 2. Pick a language folder

Open `verilog/` or `system_verilog/` and choose the template you need. Read the matching note in `explanation/` if you want the reasoning behind it.

### 3. Simulate

Any standard simulator works. Some free options:

| Tool | Notes |
| --- | --- |
| [Icarus Verilog](https://steveicarus.github.io/iverilog/) | Free, good for Verilog |
| [Verilator](https://www.veripool.org/verilator/) | Fast, supports much of SystemVerilog |
| [EDA Playground](https://www.edaplayground.com/) | Run code in the browser, no install |
| [GTKWave](https://gtkwave.sourceforge.net/) | View waveform (`.vcd`) output |

Example with Icarus Verilog:

```bash
iverilog -o sim design.v testbench.v
vvp sim
gtkwave dump.vcd
```

### 4. View the website

The `website/` folder contains a browsable version of the templates and explanations.

- **Live site:** [verilog-systemverilog-template-libr.vercel.app](https://verilog-systemverilog-template-libr.vercel.app/)
- **Run it locally:** open the `website/` folder in VS Code, right-click `index.html`, and choose **Open with Live Server**. It will open at `http://127.0.0.1:5500/`.

---

## Suggested Learning Path

1. Read the explanation for a concept
2. Open the matching template and study its structure
3. Write a small testbench and simulate it
4. Modify the design and observe the waveform changes
5. Move on to the SystemVerilog version of the same idea

---

## Contributing

Contributions are welcome. To add or improve a template:

1. Fork the repository
2. Create a branch (`git checkout -b add-new-template`)
3. Add your template and, if possible, a short explanation in `explanation/`
4. Commit and open a pull request

Please keep code readable, commented, and beginner-friendly.

## License

No license has been added yet. Add a `LICENSE` file (for example MIT) to state how others may use this work.

---

If this helps you, consider giving the repo a star.
, consider giving the repo a star.
