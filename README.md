
# 💻 Operating Systems Laboratory (BCS-401)

<p align="center">
  <img src="https://img.shields.io/badge/Language-C%20%7C%20C%2B%2B%20%7C%20Java%20%7C%20Python-blue?style=for-the-badge&logo=codeforces" alt="Languages">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Unix-orange?style=for-the-badge&logo=linux" alt="Platform">
  <img src="https://img.shields.io/badge/Academic%20Lab-Passed%20%E2%9C%95%20100%25-green?style=for-the-badge" alt="Status">
</p>

---

## 📌 Repository Overview

This repository hosts robust, highly optimized architectural simulations of core OS concepts. Each component features modular, tested implementations across **Procedural (C)**, **Object-Oriented (C++, Java)**, and **Scripting (Python)** paradigms.

> 💡 **Core Objective:** To translate abstract computing theories (e.g., race conditions, process thrashing, scheduling bottlenecks) into concrete computational modules.

---

## 🗺️ Roadmap & Algorithm Syllabus

| Core Domain | Module Identifier | Algorithm / Policy Implemented | Status |
| :--- | :---: | :--- | :---: |
| **Process Management** | `PM-01` | First-Come, First-Served (FCFS) | 🟩 Active |
| | `PM-02` | Preemptive Round Robin (RR) | 🟩 Active |
| | `PM-03` | Non-Preemptive Priority Scheduling | 🟩 Active |
| **Deadlock Control** | `DL-01` | Banker's Algorithm (Safety & Allocation) | 🟩 Active |
| **Memory Allocation**| `MA-01` | First Fit Strategy | 🟩 Active |
| | `MA-02` | Best Fit Strategy | 🟩 Active |
| | `MA-03` | Worst Fit Strategy | 🟩 Active |
| **File Systems** | `FS-01` | Contiguous File Block Allocation | 🟩 Active |

---

## 🚀 Deep-Dive: System Architecture & Design

### 🕒 1. CPU Scheduling Metrics
The scheduling models compute performance efficiency using the following formal process execution boundaries:

{Turnaround Time (TAT)} = {Completion Time (CT)} - {Arrival Time (AT)}

{Waiting Time (WT)} = {Turnaround Time (TAT)} - {Burst Time 

```text
Arrival (AT)      Execution Start        Completion (CT)
|                   |                       |
v                   v                       v
+-------------------+-----------------------+
|   Waiting (WT)    |      Burst (BT)       |
+-------------------+-----------------------+
<------------ Turnaround Time -------------->

---

### 🛡️ 2. Deadlock Avoidance (Banker's Algorithm Matrix)
Engineered around dynamic vector evaluation checks to calculate systemic vulnerability paths prior to hardware space reservation tasks:

{Need}[i][j] = {Max}[i][j] - {Allocation}[i][j]

---

### 🧠 3. Memory Fitting Evaluation
* **First Fit:** Allocates the *first* hole that is big enough. (Fastest execution)
* **Best Fit:** Allocates the *smallest* hole that is big enough. (Minimizes leftover fragments)
* **Worst Fit:** Allocates the *largest* hole available. (Leaves largest, most reusable fragments)

---

## ⚙️ Environment Setup & Toolchain Execution

Ensure you have your respective system compilers explicitly path-mapped before deployment:

### 📥 Cloning the Repository
```bash
git clone [https://github.com/shambhushekharsinha-engg/Operating-Systems-Lab.git](https://github.com/shambhushekharsinha-engg/Operating-System-Lab.git)
cd Operating-System-Lab

⚡ Compilation Commands

# C Deployment Layer
gcc -O3 ./Source/Algorithm_Name.c -o c_out && ./c_out

# C++ Object Layer
g++ -std=c++17 -O3 ./Source/Algorithm_Name.cpp -o cpp_out && ./cpp_out

# Java Runtime Virtual Environment
javac ./Source/Algorithm_Name.java && java -cp ./Source Algorithm_Name

# Python Execution Vector
python3 ./Source/Algorithm_Name.py

📊 Sample Execution Engine Analytics

========================================================================
             CPU EXECUTION TRACE GENERATION (ROUND ROBIN)
========================================================================
PID     Burst Time     Arrival Time     Turnaround Time    Waiting Time
------------------------------------------------------------------------
P1      10ms           0ms              23ms               13ms
P2      5ms            1ms              15ms               10ms
P3      8ms            2ms              21ms               13ms
------------------------------------------------------------------------
[✓] Simulation Completed Successfully.
[✓] System Integrity Verified: Safe Execution Path Ensured.
========================================================================

🎨 Repository Layout Framework

├── .github/                # CI workflows and issue templates
├── Documentation/          # Algorithm theory sheets & lab logs
├── Source/                 # Source code directories
│   ├── FCFS/               # Files grouped cleanly by algorithm name
│   ├── Bankers/
│   └── Memory_Fit/
└── README.md               # Main layout engine document


👨‍💻 Contributor Profile

Name: Shambhu Shekhar Sinha
Roll Number: 2401321530048
Course Framework: Computer Science & Engineering
<p align="center">
Developed with ❤️ for Academic & Engineering Excellence.
</p>