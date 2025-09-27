# -RISC-V-Reference-SoC-Tapeout-VSD-Program-Week-1
🔧5-day Verilog RTL workshop for week 1 : Day 1 covers iverilog, GTKWave, Yosys, Sky130; Day 2 dives into timing libs, synthesis styles; Day 3 focuses on logic optimizations; Day 4 explores GLS, sim-synth mismatch; Day 5 wraps with if/case constructs, loops, and generate blocks for scalable RTL.

🔧 Verilog RTL Design & Synthesis Workshop
Welcome to the official repository for the 5-Day Verilog RTL Design & Synthesis Workshop, a comprehensive, hands-on training program designed to equip engineers and students with practical skills in RTL design, simulation, synthesis, and verification using open-source tools.

📚 Workshop Overview
This workshop blends theory with real-world labs to help participants understand the full digital design flow—from writing Verilog code to simulating, synthesizing, and optimizing it for silicon. The sessions are structured to progressively build expertise using tools like iverilog, GTKWave, Yosys, and Sky130 PDKs.

🗓️ Daily Breakdown
Day 1: Simulation & Synthesis Foundations
Introduction to Icarus Verilog (iverilog): compiling and simulating Verilog designs

Waveform analysis using GTKWave: visualizing signal transitions and debugging

Overview of Yosys: RTL-to-gate-level synthesis flow

Labs using Sky130 PDKs: applying synthesis to real-world open-source fabrication targets Focus: Building a complete simulation and synthesis flow using open-source tools. Participants gain hands-on experience in simulating basic designs and synthesizing them for fabrication.

Day 2: Timing & Coding Strategies
Understanding timing libraries (.lib): cell delays, setup/hold constraints, and timing arcs

Hierarchical vs flat synthesis: trade-offs in modularity, optimization, and runtime

Efficient flop coding styles: reset strategies, enable logic, and synthesis-friendly patterns Focus: Writing RTL that aligns with timing constraints and synthesis goals. Participants learn how coding styles directly affect timing closure and resource usage.

Day 3: RTL Optimization Techniques
Combinational logic optimization: constant propagation, logic pruning, and gate minimization

Sequential logic optimization: state machine simplification, register balancing

Handling unused outputs: identifying and removing dead logic Focus: Improving RTL efficiency for area, power, and performance. Labs demonstrate how synthesis tools optimize logic and how designers can guide those optimizations.

Day 4: Verification & Mismatch Debugging
Introduction to Gate-Level Simulation (GLS): validating synthesized netlists

Identifying synthesis-simulation mismatches: latch inference, reset mismatches, and timing violations

Deep dive into blocking vs non-blocking assignments: simulation behavior vs synthesis interpretation

Labs on mismatch debugging using blocking statements Focus: Ensuring functional correctness post-synthesis. Participants learn to debug subtle issues that arise due to coding style and synthesis behavior.

Day 5: Control Logic & Scalable RTL
Safe use of if and case constructs: avoiding unintended latch inference and logic duplication

Labs on incomplete if and overlapping case statements: identifying synthesis warnings and functional bugs

Using for loops and generate blocks: scalable design for parameterized modules and arrays Focus: Writing robust, reusable RTL for complex systems. Participants learn how to structure control logic and scale designs using Verilog constructs.

🛠 Tools Used
Icarus Verilog

GTKWave

Yosys

Sky130 PDK

✅ Prerequisites
Basic understanding of digital logic and Verilog

Linux environment (Ubuntu recommended)

Git and terminal proficiency

🚀 Setup Instructions
bash
# Clone the repository
git clone https://github.com/your-username/verilog-rtl-workshop.git
cd verilog-rtl-workshop

# Install dependencies (example for Ubuntu)
sudo apt install iverilog gtkwave yosys

# Explore lab folders
cd Day1/
📂 Repository Structure
Code
├── Day1/         # Simulation & Synthesis labs
├── Day2/         # Timing & Coding labs
├── Day3/         # Optimization labs
├── Day4/         # Verification labs
├── Day5/         # Control logic labs
└── README.md
🎯 Learning Outcomes
By the end of this workshop, participants will:

Simulate and debug Verilog designs using open-source tools

Understand synthesis flows and timing constraints

Optimize RTL for performance and area

Validate designs through gate-level simulation

Write scalable and reusable RTL modules
