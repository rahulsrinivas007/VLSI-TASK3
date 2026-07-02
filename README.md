# VLSI-TASK3
# Task_03# Verilog RTL Design of Sequential Circuits and Flip-Flops

## 📌 Overview

This project was completed as part of the **VLSI Design Internship – Task 3**. The objective of this task is to design, implement, and simulate basic sequential circuits using Verilog HDL. The project focuses on understanding clock-driven circuits, memory elements, registers, counters, and waveform analysis.

---

## 🎯 Objectives

* Understand sequential logic behavior.
* Design and implement flip-flops using Verilog HDL.
* Develop simple registers and counters.
* Create testbenches for verification.
* Simulate and analyze waveform outputs.

---

## 🛠️ Tools Used

* Verilog HDL
* EDA Playground
* Icarus Verilog
* GTKWave
* ModelSim (Optional)

---

## 📂 Implemented Designs

### 1. D Flip-Flop

A D Flip-Flop stores one bit of data and transfers the input value to the output on the positive edge of the clock.

#### Files

* `d_flipflop.v`
* `tb_d_flipflop.v`

---

### 2. JK Flip-Flop

A JK Flip-Flop performs Hold, Reset, Set, and Toggle operations based on the values of J and K inputs.

#### Files

* `jk_flipflop.v`
* `tb_jk_flipflop.v`

---

### 3. 4-Bit Register

A 4-bit Register stores four bits of data and updates its output on the rising edge of the clock.

#### Files

* `register4.v`
* `tb_register4.v`

---

### 4. 4-Bit Binary Counter

A synchronous counter that increments its value on every positive clock edge.

#### Files

* `counter4.v`
* `tb_counter4.v`

---

## 🧪 Testbench Verification

Testbenches were developed to verify the functionality of each sequential circuit.

### Verification Includes

* Clock generation
* Input stimulus application
* Output observation
* Functional validation

---

## 📊 Simulation Results

### D Flip-Flop

* Output follows input at the clock edge.
* Correct storage of input data.

### JK Flip-Flop

* Hold operation when J=0 and K=0.
* Reset operation when J=0 and K=1.
* Set operation when J=1 and K=0.
* Toggle operation when J=1 and K=1.

### 4-Bit Register

* Correctly stores and updates 4-bit data.

### 4-Bit Counter

* Counts sequentially from 0000 to 1111.
* Resets automatically after maximum count.

---

## 📸 Output Waveforms

### D Flip-Flop

![D Flip-Flop Waveform](Screenshots/D_FF_Output.jpg)

### JK Flip-Flop

![JK Flip-Flop Waveform](/Screenshots/JK_FF_Output.jpg)

### 4-Bit Register

![Register Waveform](/Screenshots/Register_Output.jpg)

### 4-Bit Counter

![Counter Waveform](/Screenshots/Counter_Output.jpg)

---

## 📁 Repository Structure

```text
Task_03/
│
├── Task Files/
│   ├── count_tb.v
│   ├── counter.v
│   ├── d_flipflop_tb
│   ├── d_flipflop.v
│   ├── JK_FLIPFLOP.v
│   ├── JK_FLIPFLOP_TB.v
│   ├── register_tb.v
│   └── registers.v
|
├── Screenshots/
│   ├── D_FF_Output.png
│   ├── JK_FF_Output.png
│   ├── Register_Output.png
│   └── Counter_Output.png
│
├── Document
└── README.md
```

---

## 📚 Key Concepts Learned

* Sequential Logic
* Clocked Digital Circuits
* D Flip-Flop Design
* JK Flip-Flop Design
* Register Design
* Counter Design
* RTL Coding using Verilog HDL
* Testbench Creation
* Waveform Analysis

---

## 🚀 Learning Outcomes

After completing this project, I gained hands-on experience in:

* Designing sequential circuits using Verilog HDL.
* Writing synthesizable RTL code.
* Creating and executing testbenches.
* Simulating digital circuits.
* Analyzing waveform outputs for verification.

---

## 🏁 Conclusion

This project successfully demonstrates the design and simulation of fundamental sequential circuits including D Flip-Flop, JK Flip-Flop, 4-Bit Register, and 4-Bit Counter using Verilog HDL. The simulation results validate the correct functionality of all implemented modules and provide practical exposure to RTL design and verification workflows used in VLSI and FPGA development.

---
##Author

N MANOJ SAI KRISHNA
