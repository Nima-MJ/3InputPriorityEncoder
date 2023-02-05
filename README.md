# Description:
In this project, I designed two simple combinational circuits using Altera software (Quartus II) and Verilog. The project was split into two parts: Part I and Part II.

Part I: Design of a Priority Encoder
In this part of the project, I designed a 3-bit priority encoder circuit that converts a 3-bit input into a binary (2-bit) representation. I used a K-map to simplify the input and then developed a Verilog behavior model for the priority encoder. I showed the design steps in detail and simulated the Verilog model using Altera software. The Verilog code for Priority Encoder [Encoder_Verilog_1.v](https://github.com/Nima-MJ/3InputPriorityEncoder/blob/a41d9d323a99db234e02d0724c65b2d3916f2ecd/Encoder_Verilog_1.v)

Part II: Design of an N-bit comparator
In this part of the project, I designed a 4-bit comparator that compares two 4-bit numbers A and B and indicates whether the numbers are equal or which of the numbers is greater. To achieve this, I first designed a 1-bit comparator and then extended it to design a 4-bit comparator. The input to the comparator was two numbers, A and B, and the output was A < B, A = B, A > B. I started comparing the digits from the most significant bit (MSB) and then moved to the subsequent more significant bits. I used inverters and 2 and 3-input AND, NAND, OR, NOR, exclusive-OR, and exclusive-NOR gates to design the comparator. The Verilog code for 4-bit comparator [fourbitcompv.v](https://github.com/Nima-MJ/3InputPriorityEncoder/blob/a41d9d323a99db234e02d0724c65b2d3916f2ecd/fourbitcompv.v)

The details of the project results and code can be found in greater detail in the [ELG4137 pdf](https://github.com/Nima-MJ/3InputPriorityEncoder/blob/a41d9d323a99db234e02d0724c65b2d3916f2ecd/ELG4137.pdf)

# Technologies/ Languages:
- Quartus II
- Verilog

# Concepts used:
- Combinational circuit design
- Verilog behavior modeling and simulation
- Truth tables and K-map simplification
- Priority encoder design
- N-bit comparator design
- Serial cascading of 1-bit comparators to form an N-bit comparator
- Use of logical gates such as AND, NAND, OR, NOR, XOR, and XNOR
- Comparison of binary numbers and representation of their comparison results.
