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
module logicgate2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logicgates3(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by: RegisterNumber:*/


**RTL realization**
<img width="662" height="378" alt="Screenshot 2025-11-28 134436" src="https://github.com/user-attachments/assets/8f126db8-3898-469c-9830-22be378f673c" />
<img width="798" height="476" alt="Screenshot 2025-11-28 140802" src="https://github.com/user-attachments/assets/723d74dd-ecfd-4ced-b001-c1149907b73b" />


**Output:**
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/c7e5d09c-aaa6-4a7f-9adb-c405fdbfd887" />
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/21eda381-c94e-4686-ba55-91d65b3702aa" />


**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

