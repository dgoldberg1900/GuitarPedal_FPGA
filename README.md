# 🎸 FPGA Digital Guitar Pedal

This project implements a real-time digital guitar pedal using an FPGA and Verilog. The system captures a live guitar signal, processes it using digital logic to apply audio effects like distortion or delay, and outputs the modified signal to an amplifier or speaker.

##  Overview

The goal is to demonstrate real-time audio signal processing using a hardware design implemented in Verilog on an FPGA development board (e.g., Nexys A7). Effects will be selected and controlled using onboard switches and buttons.

##  Features (Planned)

- Live analog audio input via ADC
- Digital audio effects:
  - [x] Distortion
  - [ ] Delay? / Echo? (TBD)
  - [ ] Tremolo? / Bitcrusher? (TBD)
- Audio output via PWM or DAC
- Toggleable effect control
- Clean, modular HDL design

##  Project Structure

GuitarPedal_FPGA/ 
├── src/ # Verilog source files and constraints 
├── docs/ # Diagrams, screenshots, or additional documents 
├── demo_video.mp4 # Optional presentation/demo video 
└── README.md # This file

##  Getting Started

1. Clone the repo
2. Open project in Vivado
3. Add all files under `src/` as sources
4. Apply the `guitar_pedal.xdc` constraints
5. Synthesize, implement, and program the bitstream to test

##  Authors

- Daniel Goldberg (dgoldberg1900)
- James Kaddissi (James's GitHub name)

##  Notes

This README will be updated as the project progresses. Stay tuned for demos, waveform visuals, and final performance results.

