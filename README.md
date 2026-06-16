markdown
# ⚡ Mainscraft Internship – Task 2  
**Project:** SystemVerilog Implementation of Basic Gates, Half Adder, and Full Adder  

---

## 📌 Overview
This task demonstrates the design and simulation of fundamental digital circuits using **SystemVerilog (.sv)**:
- Six Basic Logic Gates (AND, OR, NOT, NAND, NOR, XOR)  
- Half Adder
- Full Adder  

These modules are the building blocks of digital electronics. The project verifies their functionality through structured testbenches and waveform analysis.

---

## 📂 Repository Structure
mainscraft-internship/

src/
basic_gates.sv
half_adder.sv
full_adder.sv

testbench/
tb_basic_gates.sv
tb_half_adder.sv
tb_full_adder.sv

result/
waveform_gates.png
waveform_half.png
waveform_full.png

docs/
task2_report.pdf

redme.md



---

## 🛠️ How to Run
1. Open the project in **EDA Playground**, **ModelSim**, or **Quartus**.  
2. Load the respective `.sv` source file (`basic_gates.sv`, `half_adder.sv`, `full_adder.sv`) along with its testbench.  
3. Run the simulation to generate waveforms.  
4. Verify outputs against the expected truth tables.  

---

## 📊 Expected Results
- **Basic Gates:** Outputs match standard truth tables for all six gates.  
- **Half Adder:** Produces correct `sum` and `carry` outputs.  
- **Full Adder:** Correctly computes `sum` and `carry` for three inputs.  

---

## 🎯 Learning Outcomes
- Implementing digital circuits in **SystemVerilog**.  
- Writing modular testbenches for verification.  
- Validating designs using waveform simulation tools.  

---

## ✅ Deliverables
- Source files:  
  - `basic_gates.sv`  
  - `half_adder.sv`  
  - `full_adder.sv`  
- Testbench files for each design.  
- Simulation results (waveform screenshots).  
- Task 2 Report (`Task2_Report.pdf`).  

---

