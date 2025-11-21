# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:s.vazhiga banu 
RegisterNumber:25014707


**RTL realization**
<img width="1913" height="1186" alt="Screenshot 2025-11-21 214638" src="https://github.com/user-attachments/assets/2d4c22f4-4c07-4517-9bb3-a7219211398a" />

**Output:**

**RTL**

**Timing Diagram**
<img width="1920" height="1200" alt="Screenshot 2025-11-21 221723" src="https://github.com/user-attachments/assets/366b8e90-59ea-4e7c-a7ca-5c5943128cee" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

