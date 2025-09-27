🚀 RISC-V Reference SoC Tapeout – VSD Program Week 1
🔧 5-Day Verilog RTL Workshop This repository documents Week 1 of the VSD Program, focused on Verilog RTL design and synthesis. Each day builds progressively:

Day 1: iverilog, GTKWave, Yosys, Sky130

Day 2: Timing libraries, synthesis styles

Day 3: Logic optimizations

Day 4: GLS, sim-synth mismatch

Day 5: if/case constructs, loops, generate blocks

🔧 Verilog RTL Design & Synthesis Workshop
Welcome to the official repository for the 5-Day Verilog RTL Design & Synthesis Workshop, a hands-on training program designed to equip engineers and students with practical skills in RTL design, simulation, synthesis, and verification using open-source tools.

📚 Workshop Overview
This workshop blends theory with real-world labs to help participants understand the full digital design flow—from writing Verilog code to simulating, synthesizing, and optimizing it for silicon. Tools used include iverilog, GTKWave, Yosys, and Sky130 PDKs.

🗓️ Daily Breakdown
Day 1: Simulation & Synthesis Foundations
Icarus Verilog (iverilog): compiling and simulating Verilog designs

GTKWave: waveform visualization and debugging

Yosys: RTL-to-gate-level synthesis flow

Labs using Sky130 PDKs Focus: Build a complete simulation and synthesis flow using open-source tools.

Day 2: Timing & Coding Strategies
Timing libraries (.lib): cell delays, setup/hold constraints

Hierarchical vs flat synthesis: modularity vs optimization

Flop coding styles: reset logic, enable signals Focus: Write RTL aligned with timing and synthesis goals.

Day 3: RTL Optimization Techniques
Combinational logic: constant folding, gate pruning

Sequential logic: FSM simplification, register balancing

Unused outputs: dead logic elimination Focus: Improve RTL efficiency for area, power, and performance.

Day 4: Verification & Mismatch Debugging
Gate-Level Simulation (GLS): validating synthesized netlists

Synthesis-Simulation mismatches: latch inference, reset mismatches

Blocking vs non-blocking assignments Focus: Debug functional mismatches and validate post-synthesis behavior.

Day 5: Control Logic & Scalable RTL
if and case constructs: avoiding latch inference

Labs on incomplete and overlapping cases

for loops and generate blocks for scalable design Focus: Write reusable, parameterized RTL for complex systems.

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
git clone https://github.com/kaushikbarman574-max/verilog-rtl-workshop.git
cd verilog-rtl-workshop

# Install dependencies (example for Ubuntu)
sudo apt install iverilog gtkwave yosys
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

📝 Summary
This repository documents a structured 5-day workshop designed to teach Verilog RTL design and synthesis using open-source tools. Each day builds on the previous, starting with simulation fundamentals and progressing through timing analysis, logic optimization, verification techniques, and scalable RTL coding practices. Participants gain hands-on experience with tools like iverilog, GTKWave, Yosys, and Sky130 PDKs, while learning to write efficient, synthesis-friendly Verilog code. By the end of the workshop, attendees are equipped to simulate, synthesize, optimize, and verify digital designs in a real-world open-source flow.

🤝 Contributing
Contributions are welcome! If you'd like to improve documentation, add new labs, or enhance tool integration, feel free to submit a pull request. For major changes, please open an issue first to discuss your ideas.

📬 Contact
For questions, feedback, or collaboration inquiries, reach out via GitHub Issues.
