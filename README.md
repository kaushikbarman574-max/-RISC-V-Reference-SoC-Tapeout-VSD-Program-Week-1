# -RISC-V-Reference-SoC-Tapeout-VSD-Program-Week-1
🔧5-day Verilog RTL workshop for week 1 : Day 1 covers iverilog, GTKWave, Yosys, Sky130; Day 2 dives into timing libs, synthesis styles; Day 3 focuses on logic optimizations; Day 4 explores GLS, sim-synth mismatch; Day 5 wraps with if/case constructs, loops, and generate blocks for scalable RTL.
🔧 Verilog RTL Design & Synthesis Workshop
Welcome to the official repository for the 5-Day Verilog RTL Design & Synthesis Workshop, a comprehensive, hands-on training program designed to equip engineers and students with practical skills in RTL design, simulation, synthesis, and verification using open-source tools.

📚 Workshop Overview
This workshop blends theory with real-world labs to help participants understand the full digital design flow—from writing Verilog code to simulating, synthesizing, and optimizing it for silicon. The sessions are structured to progressively build expertise using tools like iverilog, GTKWave, Yosys, and Sky130 PDKs.

🗓️ Daily Breakdown
Day 1: Simulation & Synthesis Foundations
Introduction to Icarus Verilog (iverilog) and GTKWave

Labs on simulation and waveform analysis

Overview of Yosys for logic synthesis

Labs using Sky130 PDKs Outcome: Build and simulate basic RTL designs, synthesize using open-source flows.

Day 2: Timing & Coding Strategies
Understanding .lib timing files

Hierarchical vs flat synthesis approaches

Efficient flop coding styles Outcome: Write synthesis-friendly RTL and understand timing-driven synthesis.

Day 3: RTL Optimization Techniques
Combinational and sequential logic improvements

Handling unused outputs Outcome: Optimize RTL for area, power, and performance.

Day 4: Verification & Mismatch Debugging
Gate-Level Simulation (GLS)

Synthesis-Simulation mismatches

Blocking vs non-blocking assignments Outcome: Validate post-synthesis behavior and debug functional mismatches.

Day 5: Control Logic & Scalable RTL
Safe use of if and case constructs

Labs on incomplete and overlapping cases

for loops and generate blocks Outcome: Develop scalable, reusable RTL modules.

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


