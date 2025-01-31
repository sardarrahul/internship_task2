# RAM DESIGN 
*COMPANY NAME : CODTECH IT SOLUTION*

*NAME : RAHUL SARDAR*

*INTERN ID : CT08IRH*

*DOMAIN : VLSI*

*BATCH DURATION : January 5th, 2025 to February 5th, 2025*

*MENTOR NAME : NEELA SANTOSH*

# Introduction and Overview 
In modern digital systems, Static Random-Access Memory (SRAM) is widely 
used for high-speed data storage. For this project, I designed a simple 4x4 
SRAM module using Verilog, a hardware description language. The module 
was simulated to validate its functionality and understand how read and write
operations are handled in a memory array. This project gave me deeper insight 
into how memory operations are controlled, and it helped improve my 
understanding of digital logic design. 

# RTL Design Overview 
The SRAM design focuses on two main operations: 
1. Write Operation: When the write enable (we) signal is high, data is 
written to the specified memory location. 
2. Read Operation: When we is low, data is read from the memory 
location and presented on the data_out signal.
 ![image](https://github.com/user-attachments/assets/d17f97c1-c912-4fcd-b495-d3f1b53e63d2)

The module uses a clock signal (clk) for synchronization, ensuring memory 
operations occur at the correct time. The design allows for simple and efficient 
control of memory access.

 # Waveform Analysis and Simulation 
The simulation of the design helped validate the functionality of the SRAM 
module: 
• During write operations (we = 1), data is stored at the specified memory 
address, but the data_out remains unchanged. 
• During read operations (we = 0), data_out reflects the value stored at the 
specified memory address.
![image](https://github.com/user-attachments/assets/fd8d26e9-820e-4299-86bd-2a99ff4d3325)

The waveform analysis confirmed the correct behavior of the SRAM, with 
proper synchronization of the signals.

# CONCLUSION
The 4×4 SRAM module, designed using Verilog, efficiently performs read and write operations with proper clock synchronization. The design ensures data is correctly stored and retrieved based on control signals. Simulation results validate the correct functionality, confirming accurate memory access and operation.
