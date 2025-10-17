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
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: K DARREN JOSEPH
RegisterNumber:*/ 25013340


**RTL realization**

**Output:** 
![095f3c0a-3d75-44a1-9b70-2657bd7e16f7](https://github.com/user-attachments/assets/9a704f81-7e5e-4c00-b99d-e20fb1b7c238)

![f87c78c6-0be3-4023-af9f-a07eaf66230e](https://github.com/user-attachments/assets/3d16f1a1-f93b-42d1-9d91-e4b45b9e6ca6)


**RTL**

**Timing Diagram**
![63f21153-f84d-4921-bf0a-2b091837da1e](https://github.com/user-attachments/assets/3ecde1cf-2c08-4050-8dff-27ddd307176d)
![d8da7935-703a-4757-bbbd-68ab605e0c02](https://github.com/user-attachments/assets/264a43fd-e884-42ef-8248-b9e5c025543b)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

