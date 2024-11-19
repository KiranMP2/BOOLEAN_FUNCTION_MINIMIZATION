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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

PROGRAM CODE

PART 1

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule



PART 2

module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


Developed by: RegisterNumber:24000839


**RTL realization**

**Output:**

**RTL**

part 1

![Screenshot 2024-11-12 051028](https://github.com/user-attachments/assets/b9adb0fc-4b07-4bd3-b1df-6c34c88802ee)

part 2

![Screenshot 2024-11-19 034234](https://github.com/user-attachments/assets/ba993afa-d9d0-46b4-bdb0-326ac714cefb)



**Timing Diagram**

part 1

![Screenshot 2024-11-12 051132](https://github.com/user-attachments/assets/633684a7-1be4-449d-bc6a-83da029108b1)

part2 

![Screenshot 2024-11-19 034407](https://github.com/user-attachments/assets/fcc5382a-39cf-40b0-befe-7c45efe8013b)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

