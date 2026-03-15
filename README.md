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
module de2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~b&~d | a&b&~c | ~a&b&d;
assign f2 = ~y&z | x&y | w&y;
endmodule
```
Developed by:Tharunika.E

RegisterNumber:212225040470


**RTL realization**

https://private-user-images.githubusercontent.com/231869966/560688735-2214ff12-d4c8-415b-b585-1b7e823430f0.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM1NzQ3NzUsIm5iZiI6MTc3MzU3NDQ3NSwicGF0aCI6Ii8yMzE4Njk5NjYvNTYwNjg4NzM1LTIyMTRmZjEyLWQ0YzgtNDE1Yi1iNTg1LTFiN2U4MjM0MzBmMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxNVQxMTM0MzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lMzBjYTczYzE3OTZhNTAwMjg0YmEzYjUzMWM0NmU1Yzk5MDFjMmMwZTExYzViZWJlNTdlYTUzNzJjODVlNzYzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.H_78PIu8KcPYSO--92v3K4kDXWGG4XNk7ErtTT1Nivc

**Output:**

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

