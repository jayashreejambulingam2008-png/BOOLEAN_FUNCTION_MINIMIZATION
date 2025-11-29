# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
(i) module DEexp2n(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

(ii) module DEexp2new2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
Developed by: JAYASHREE J RegisterNumber: 25014460*/

**RTL**


(i)
<img width="1600" height="893" alt="image" src="https://github.com/user-attachments/assets/371f5e0a-1fd5-4a47-9d6b-53cd870538c9" />

(ii)
<img width="1600" height="904" alt="image" src="https://github.com/user-attachments/assets/85571b3f-9c68-45c6-896d-c29f3e7bb334" />

**Output**


<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/308c9701-2185-44dc-9fba-6dd7f7ce2a65" />


<img width="1600" height="901" alt="image" src="https://github.com/user-attachments/assets/f77dab9e-cce5-453a-bb6e-b35625a34134" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

