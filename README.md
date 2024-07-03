# SwissChronometer

## Description

The SwissChronometer project is an FPGA-based chronometer designed to operate with nanosecond precision. Written in VHDL, this project implements a high-precision timing mechanism suitable for accurate measurement of elapsed time in milliseconds, seconds, and minutes. The chronometer includes debounced start and reset functionalities to ensure reliable operation. The design has been tested using a VHDL test bench and the Vivado Simulator (XSIM).

## Features

- **High Precision Timing:** Operates with nanosecond precision.
- **Debounced Inputs:** Includes debounced start and reset signals to ensure stable operation.
- **Multiple Time Units:** Measures time in milliseconds, seconds, and minutes.
- **Modular Design:** Utilizes separate components for debouncing and timing logic.

## Setup Instructions

### Prerequisites

- Xilinx Vivado Design Suite
- FPGA development board (e.g., Xilinx FPGA)
- Knowledge of VHDL and FPGA development

### Steps

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/SwissChronometer.git
   cd SwissChronometer
