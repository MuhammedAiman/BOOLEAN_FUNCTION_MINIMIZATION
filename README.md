# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-10-29 at 14 17 16_94e1c11c](https://github.com/user-attachments/assets/95ddb2b3-1ce1-4f82-8288-46a3b5e374d2)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Muhammed Aiman S RegisterNumber:24901053

**Output:**

**RTL**
![exp2](https://github.com/user-attachments/assets/5a5f9da2-0af9-46a5-8d4c-08fb8e7ef703)


**Timing Diagram**
![Screenshot 2024-10-23 094705](https://github.com/user-attachments/assets/49d73e09-52fa-44b1-b0dc-8e007751ccac)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

