# UART-RECEIVER

Overview
UART Receiver implemented in Verilog HDL and 

Specifications
- Baud Rate: 115200 bps
- System Clock: 25 MHz
- Data Bits: 8
- Stop Bits: 1
- Synchronizer: 2-stage

 FSM States
- IDLE
- START
- RECV
- STOP

Features
- UART frame reception
- Metastability mitigation
- Data ready indication

Tools
- Verilator
- GTKWave
- Xilinx Vivado

Results


## How to Run
chmod +x run.sh
./run.sh