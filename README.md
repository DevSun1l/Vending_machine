# Trace-Backed Vending Machine FSM Visualizer

A high-fidelity, web-based visualization dashboard for VHDL-based Vending Machine Finite State Machines (FSM). This tool maps execution traces from hardware simulations to an interactive, synchronized dashboard.

## 🚀 Features

- **Unified Dashboard**: All system views (FSM, Waveform, FPGA, Registers, Trace Table) are visible simultaneously on a single screen.
- **Interactive Trace Stepping**: Cycle through testbench execution steps and see real-time updates across all visualization layers.
- **Physical FPGA Mapping**: Visualizes how VHDL entities map to a physical FPGA board (Cyclone V), including glowing signal traces, 7-segment displays, and status LEDs.
- **Logic Analyzer Waveform**: Responsive waveform viewer synchronized with the 50MHz hardware clock (20ns cycles).
- **Premium Dark UI**: A modern, responsive design inspired by high-end algorithm visualizers, featuring a sleek dark theme with cyan accents.

## 🛠️ Technology Stack

- **HTML5 & CSS3**: Custom layout using CSS Grid and Flexbox for a responsive experience.
- **Vanilla JavaScript (ES6)**: Core logic, trace management, and canvas-based hardware rendering.
- **Canvas API**: Used for rendering high-performance waveforms and physical PCB layouts.

## 📂 Project Structure

- `index.html`: The core application containing the UI, Styles, and Logic.
- `README.md`: Project documentation.

## 🕹️ How to Use

1. **Select a Scenario**: Choose from the "Scenarios" list in the sidebar (e.g., Normal Purchase, Card Authorization, Timeout).
2. **Step Through**: Use the **Next**, **Prev**, and **Reset** buttons to manually cycle through hardware cycles.
3. **Auto-Play**: Click **Play Trace** to watch the state machine execute automatically.
4. **Analyze**: Observe how the FSM transitions correlate with waveform changes and physical FPGA pin outputs.

## 🔧 Installation & Deployment

Since this is a client-side web application, no installation is required.

1. Clone the repository:
   ```bash
   git clone https://github.com/DevSun1l/Vending_machine.git
   ```
2. Open `index.html` in any modern web browser.

---
Developed with ❤️ by [DevSun1l](https://github.com/DevSun1l)
