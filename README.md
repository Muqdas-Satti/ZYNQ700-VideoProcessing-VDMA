
This project demonstrates a basic video processing pipeline using Xilinx Vivado, featuring the following components:
# Video Processing Project using Vivado

## Overview

This project demonstrates a basic video processing pipeline using Xilinx Vivado, featuring the following components:

- **Video Direct Memory Access (VDMA)**
- **Test Pattern Generator (TPG)**
- **VGA Display**

The system generates a test pattern using the TPG, transfers the video data through VDMA, and displays it on a VGA screen.

## Detailed Tutorial

For a step-by-step guide on how to build this project, refer to the detailed blog tutorial [here](https://your-blog-link.com).

## Project Structure


├── src/ # Source files
├── sdk/ # SDK
└── XPR/ #pROJECT FILE

### Steps to Run

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-repo/video-processing.git
   cd video-processing

Open Vivado and load the project file (video_processing.xpr).
Run Synthesis, Implementation, and Bitstream Generation in Vivado.
Program the FPGA with the generated bitstream.
Connect the VGA Monitor to the board and verify the output.
