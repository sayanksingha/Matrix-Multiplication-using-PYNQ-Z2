# Matrix-Multiplication-using-PYNQ-Z2
This project implements hardware-accelerated matrix multiplication on the Xilinx PYNQ-Z2 FPGA board. The design uses a custom IP core developed in Vitis HLS, integrated with AXI4-Stream and AXI4-Lite interfaces, and controlled via Python running on the PYNQ platform.

Matrix multiplication is a fundamental operation in signal processing, image computation, and machine learning. This project demonstrates how to accelerate matrix multiplication using FPGA hardware for parallel computation.

Workflow:

Matrix_Multiplication_PYNQ-Z2
│
├── HLS
│   ├── matrix_mult.cpp
│   └── matrix_mult_test.cpp
│
├── Vivado
│   ├── block_design
│   └── bitstream
│
├── PYNQ
│   ├── matrix_mult.bit
│   ├── matrix_mult.hwh
│   └── matrix_mult.ipynb
│
└── README.md
