# BOOLEAN_FUNCTION_MINIMIZATION

Developed by: MOHAMMED SHAMEER M
RegisterNumber: 212225040251

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
~~~

MINIMIZATION OF BOOLEAN FUNCTION
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
~~~

**RTL realization**
<img width="929" height="621" alt="image" src="https://github.com/user-attachments/assets/e9528905-0954-46eb-8972-bc89fcb32d6e" />

**Output:**
<img width="852" height="558" alt="image" src="https://github.com/user-attachments/assets/ae4a9343-91b5-418f-9853-9c5585b7d31d" />

**RTL**
<img width="1818" height="801" alt="image" src="https://github.com/user-attachments/assets/05ec5b24-a677-4f90-ac31-725e9ea889a3" />

**Timing Diagram**
<img width="1818" height="801" alt="image" src="https://github.com/user-attachments/assets/bcafa30d-38ee-4dfa-b802-a08eb217f019" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

