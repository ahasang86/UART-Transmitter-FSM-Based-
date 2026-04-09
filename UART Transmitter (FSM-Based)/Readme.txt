# UART Transmitter (FSM-Based) – Verilog

This project implements a UART Transmitter using a Moore-style FSM.  
The design includes four states: **IDLE**, **START**, **DATA**, and **STOP**,  
and handles bit shifting, start/stop framing, and busy signaling.

---

## 🔧 Features
- Moore FSM architecture
- 8-bit serial transmission
- Start/stop bit generation
- Busy flag for transmission status
- Clean, readable Verilog with full comments
- Fully working testbench

---

## 📂 File Structure
/src  
 ├── uart_tx.v  
 └── tb_uart_tx.v  

---

## 🧪 Simulation
The testbench verifies:
- Start bit generation  
- 8-bit LSB-first transmission  
- Stop bit timing  
- Busy signal behavior  

Compatible with:
- ModelSim / QuestaSim  
- Xilinx Vivado  
- Intel Quartus  

---

## 🚀 Future Enhancements
- UART Receiver (RX)
- Baud rate generator
- Full-duplex UART module
- AXI-Lite to UART bridge

---

## 📜 License
MIT License
