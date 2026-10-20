# cadence-full-adders
Comparative analysis of four full-adder architectures using Cadence Virtuoso and 180 nm GPDK technology. Evaluates power consumption, propagation delay, and transistor count. Identifies Transmission Gate logic as the best-performing design in the reported simulations for low-power, high-speed VLSI applications.
This project compares four full-adder circuit architectures using CMOS technology and Cadence Virtuoso. The designs are evaluated based on power consumption, propagation delay, and transistor count to identify a suitable architecture for efficient VLSI applications.

Objectives

Design and simulate different full-adder architectures.

Compare power consumption, sum delay, and carry delay.

Analyze transistor count and circuit complexity.

Identify a suitable architecture for low-power, high-speed digital circuits.

Architectures Implemented

NAND-Only Logic

Hybrid AND–OR–XOR Logic

Custom CMOS Transistor-Level Design

Transmission Gate (TG)-Based Logic

Tools and Technologies

Cadence Virtuoso

Spectre Simulation

180 nm GPDK Technology

CMOS Circuit Design

VLSI System Design

Performance Comparison

Architecture

Transistor Count

Sum Delay (ps)

Carry Delay (ps)

Power (W)

NAND-Only

36

123.94

93.61

371 × 10⁻⁶

AND–OR–XOR Hybrid

42

120.05

142.37

493.2 × 10⁻⁶

Custom CMOS

28

177.86

143.3

173.9 × 10⁻⁹

Transmission Gate

20

67.606

34.92

7.063 × 10⁻⁶

Note: Values are reproduced from the project report and have not been independently revalidated.

Key Findings

The Transmission Gate implementation achieved the lowest reported sum and carry delays.

It used the lowest number of transistors among the four architectures.

The NAND-only and hybrid implementations provided useful baselines for comparing logic-level designs.

The custom CMOS implementation demonstrated a different trade-off between transistor count, power, and delay.

Applications

Full adders are fundamental building blocks in:

Arithmetic Logic Units (ALUs)

Microprocessors and digital processors

Digital Signal Processing (DSP) systems

VLSI arithmetic circuits

Future Improvements

Optimize transistor sizing.

Perform layout design and parasitic extraction.

Evaluate process and temperature variations using Monte Carlo analysis.

Extend the study to multi-bit adders and larger arithmetic circuits.

Contributors

Christina Grace E

S. A. Harini

Smruthi B

Academic Information

Course: BECE303L – VLSI System Design
Institution: Vellore Institute of Technology, Chennai
Project Guide: Dr. Girija Shankar Sahoo[Project-template-a4 (1).pdf](https://github.com/user-attachments/files/33709153/Project-template-a4.1.pdf)

