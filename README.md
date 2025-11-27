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
module digital2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logicgates2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by: RegisterNumber:*/


**RTL realization**
<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/32adc7cd-0564-45c5-8eee-14a6e481f1ac" />
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/7721550a-4ad2-439f-b65c-22032afa4bfd" />

**Output:**
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/b949ae85-b962-4fde-95ee-25b5efaebd38" />
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/241d12d9-132b-490c-ba9d-cb95b534b410" />

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

