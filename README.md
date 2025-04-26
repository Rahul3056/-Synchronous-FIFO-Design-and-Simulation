
# 📦 Synchronous FIFO Design and Simulation

## Overview
This project demonstrates the design and verification of a **Synchronous FIFO (First In, First Out)** memory module using **Verilog HDL**.  
It covers a complete RTL implementation, an advanced testbench, and simulation waveforms.

The FIFO is designed to handle concurrent `push` and `pop` operations with proper `full` and `empty` flag handling.

---

## ✨ Features
- Parameterizable buffer depth and data width.
- Synchronous read and write operations.
- Full and Empty status flag generation.
- FIFO counter to monitor occupancy.
- Thorough verification via custom Testbench.
- Waveform generation using EPWave.

---

## 🛠️ Project Structure
```
├── fifo.v             # RTL Design: Synchronous FIFO Module
├── tb_fifo.v          # Testbench: Push/Pop operations, Verification Tasks
├── waveform.png       # Waveform screenshot (optional)
└── README.md          # Project Documentation
```

---

## 🚀 How to Simulate
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/synchronous-fifo.git
   cd synchronous-fifo
   ```
2. Use any Verilog simulator (e.g., ModelSim, VCS, etc.) or simulate directly on **EDA Playground**.

✅ **Direct EDA Playground Link:** [https://www.edaplayground.com/x/XTHm] 

---

## 📈 Simulation Waveform
Sample waveform showing push/pop operations and FIFO counter:
![WhatsApp Image 2025-04-26 at 20 39 00_d5565422](https://github.com/user-attachments/assets/21c78d22-9a41-441c-a190-50b9a00f1313)


---

## 🔍 Key Learnings
- Importance of managing synchronous resets in FIFO designs.
- Handling full and empty conditions without causing data loss or overflow.
- Power of waveform analysis for debugging hardware designs.

---

## 📬 Contact
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/rahulteradal/) or contribute to the project!
