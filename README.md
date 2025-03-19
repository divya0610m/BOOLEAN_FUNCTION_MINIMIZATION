### Name: DIVYA LAKSHMI M

### Reg.No: 212224040082

## BOOLEAN_FUNCTION_MINIMIZATION

**Aim:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Theory**

In this experiment, combinational logic functions are implemented using Verilog HDL and verified through simulation in Quartus software. The given functions F1 and F2 are in Sum of Products (SOP) form, which are combinations of AND, OR, and NOT gates.

-> F1 is a 4-variable logic function with inputs A, B, C, D.
-> F2 is a 4-variable logic function with inputs w, x, y, z.

Using Verilog, the Boolean expressions are coded using assign statements, which create combinational circuits. The design is then compiled and simulated in Quartus, where input combinations are applied, and outputs F1 and F2 are observed in the waveform to verify correctness.

This process helps in understanding digital circuit design and simulation using HDL and FPGA tools.


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

![ex 2 prog](https://github.com/user-attachments/assets/9b6f7888-35b9-4d0f-ac26-0c47939d7903)


**Truth Table**

https://github.com/user-attachments/assets/180440d0-631d-45bf-a85a-4508c9f41e65
https://github.com/user-attachments/assets/e7443311-e06d-405a-9194-a60e492f0585

**RTL**

![ex 2 dia](https://github.com/user-attachments/assets/0bf90835-30a3-44fd-bf12-056eed920ca1)

**Waveform**

![ex 2 sim](https://github.com/user-attachments/assets/9f514bbb-2e32-4630-85fa-4ae25d00bf72)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

