# PDS project: Sobel edge detection simulation

The goal of this project is to implement the Sobel operator for edge detection on an image using FPGA technology. The task involves designing a method for transferring and processing a larger image (512 × 512 pixels) on an FPGA board, describing the applied techniques, and discussing potential improvements to the implementation.

The digital circuit is described in Verilog HDL and developed using the Xilinx ISE WebPACK 14.7 development environment. Due to hardware limitations preventing deployment on the Spartan-3E XC3S500E board, a detailed simulation of the conceptual logic design was created and analyzed.

- Usage: https://fesb-my.sharepoint.com/:v:/g/personal/agrbav02_fesb_hr/Ea0Y55TYeYlHrej2nr-afGwBipJPtLrbdfHmO7G69aj-eA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=01dx9d

- sim/sobel/run_sobel.sh:
  -  dependencies:
      - VM Linux Oracle 6.7
      - python 3.6.5 and up (VM Linux Oracle 6.7)
      - pip cmd (VM Linux Oracle 6.7)
