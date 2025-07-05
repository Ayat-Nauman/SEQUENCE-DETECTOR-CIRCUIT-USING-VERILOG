# Sequence Detector for "01111110" Pattern
A Verilog-based finite state machine that detects the "01111110" bit pattern with synchronous operation and proper reset functionality.

### Project Overview
This project implements a sequence detector in Verilog HDL that identifies the specific bit pattern "01111110" in an input stream. The design includes a finite state machine (FSM) with 8 states, synchronous operation, and both overlapping and non-overlapping detection capabilities.

### Key Features
- Verilog implementation of a Moore-type finite state machine
- Detects the sequence "01111110" in an input bit stream
- Includes complete testbench with waveform generation
- Synthesizable RTL design
- Detailed documentation including state diagram and timing analysis

### Requirements
- Verilog simulator (Icarus Verilog, ModelSim, etc.)
- Waveform viewer (GTKWave) for viewing simulation results

## How to run the simulation file?
- Download the zip file from the repository.
- Open Quartus Prime and go to "Open projects".
- Open the project file with a .qpf extension. The file will be named "sequence_detector2.qpf".
  
### Results
The testbench demonstrates successful detection of the "01111110" sequence with proper timing and state transitions.

### Future Enhancements
- Parameterize the sequence for different patterns
- Add configurable overlapping/non-overlapping mode
- Implement as an AXI-stream interface for system integration

---
