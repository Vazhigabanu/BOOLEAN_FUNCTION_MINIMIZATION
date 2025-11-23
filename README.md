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
![truth table Image 2025-11-22 at 23 31 55_8eb8372c](https://github.com/user-attachments/assets/bce4a884-a7eb-4d66-8547-66eb48b2fd0d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Developed by:s.vazhiga banu 

RegisterNumber:25014707
```
i) 
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
ii) 
module funct2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
```

**RTL realization**
<img width="1791" height="925" alt="Screenshot 2025-11-23 212510" src="https://github.com/user-attachments/assets/c96d419e-a8a8-465c-abda-2a5e2d8c9ff7" />
<img width="1794" height="930" alt="Screenshot 2025-11-23 212534" src="https://github.com/user-attachments/assets/7dc5beb0-764a-43a3-879b-6195e595bc3b" />

**Output:**
<img width="1790" height="926" alt="Screenshot 2025-11-23 212553" src="https://github.com/user-attachments/assets/89ed66ba-5b41-4262-b6b1-6aa5f32eef92" />
<img width="1786" height="927" alt="Screenshot 2025-11-23 212618" src="https://github.com/user-attachments/assets/c7940f50-60bf-4423-bdad-4181bd64ea1d" />

**RTL**
<img width="1920" height="1200" alt="Screenshot 2025-11-23 213303" src="https://github.com/user-attachments/assets/b19f8c36-44ce-425d-804d-ac3b472cdeda" />
<img width="1920" height="1200" alt="Screenshot 2025-11-23 213118" src="https://github.com/user-attachments/assets/fd4dc798-84ba-4907-9dfb-7b163f4aceba" />

**Timing Diagram**


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

