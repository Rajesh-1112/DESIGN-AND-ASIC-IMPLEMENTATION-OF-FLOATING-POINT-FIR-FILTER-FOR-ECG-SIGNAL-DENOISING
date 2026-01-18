# DESIGN-AND-ASIC-IMPLEMENTATION-OF-FLOATING-POINT-FIR-FILTER-FOR-ECG-SIGNAL-DENOISING
This project focuses on designing and implementing a floating-point FIR filter for ECG signal denoising using IEEE 754 arithmetic. MATLAB and Verilog are used, along with Rectangular, Hanning, Hamming, and Blackman window techniques, to achieve accurate and hardware-efficient filtering for ASIC/FPGA biomedical applications.



## Objectives
- Design a floating-point FIR filter for ECG signal denoising  
- Implement IEEE 754 compliant floating-point arithmetic units  
- Apply and compare different window functions  
- Validate hardware results with MATLAB outputs  
- Develop an ASIC/FPGA-ready FIR filter architecture  


##  Tools & Technologies
- **MATLAB** – ECG signal processing, FIR design, windowing  
- **Verilog HDL** – Hardware design and implementation  
- **IEEE 754 Standard** – Single-precision floating-point arithmetic  
- **Vivado / ModelSim** – Simulation and verification  


##  Features
- 10-tap floating-point FIR filter  
- Pipelined floating-point adder and multiplier  
- Supported windowing techniques:
  - Rectangular  
  - Hanning  
  - Hamming  
  - Blackman  
- MATLAB–Verilog output verification  
- Suitable for ASIC and FPGA biomedical applications
