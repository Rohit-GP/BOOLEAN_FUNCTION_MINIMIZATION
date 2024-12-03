# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

 ```
module labone(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|(w & y)|(x & y));
endmodule
```

```
module Lab(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

Developed by: Rohit GP 

RegisterNumber: 24900185



**RTL**

f1
![Screenshot (44)](https://github.com/user-attachments/assets/5ab5f0d9-7d45-405b-84f9-0865b749d359)

f2
![Screenshot (47)](https://github.com/user-attachments/assets/91535051-f28c-43e4-9c0c-f46b7b40332b)


**Output:**

f1
![Screenshot (45)](https://github.com/user-attachments/assets/e973a53d-3063-4c94-8a66-ca2a4a97befa)

f2
![Screenshot (48)](https://github.com/user-attachments/assets/677b14a7-821d-49ca-85c6-c8d5d76438de)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

