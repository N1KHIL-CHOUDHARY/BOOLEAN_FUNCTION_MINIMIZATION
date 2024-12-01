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


Developed by: RegisterNumber:(NIKHIL H)24900366


**RTL realization**
 
**Output:**
 ![WhatsApp Image 2024-12-01 at 14 19 50_63bf36b4](https://github.com/user-attachments/assets/43a8045e-404c-4396-918f-6c926257978e)


**RTL**
   ![WhatsApp Image 2024-12-01 at 14 19 51_f063a62b](https://github.com/user-attachments/assets/f3a66c2c-29f2-449d-8eb0-7202bcb29f10)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

