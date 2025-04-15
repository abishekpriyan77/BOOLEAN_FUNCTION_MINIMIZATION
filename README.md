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
```
 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

 module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule
```

**Developed by: Abisheik priyan V**



**RegisterNumber:212224230005**


**RTL realization Output:**

![Screenshot 2025-04-15 111943](https://github.com/user-attachments/assets/bae98f50-ab78-4776-9271-a0891bc121f2)
![Screenshot 2025-04-15 112026](https://github.com/user-attachments/assets/be220486-8011-483d-95a5-8c75ab65e028)

**RTL Timing Diagram**
![exp2 1](https://github.com/user-attachments/assets/7d6d8aa7-7b94-439f-a1ab-66067ee5db1a)

![exp2 2](https://github.com/user-attachments/assets/54301c80-00bf-4c79-a61a-e0bf86d8fde4)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

