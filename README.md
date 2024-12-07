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

```

FUNCTION 1 K-MAP

```

![image](https://github.com/user-attachments/assets/d09598ec-d0d0-406d-9a7b-d3fbb5443aa8)

```

FUNCTION 2 K-MAP

```

![image](https://github.com/user-attachments/assets/f38d1799-15f9-4759-8e0b-a291f1e7bc15)


**Procedure**

```


1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

```

**Program:**
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


```

FUNCTION 1
 module function1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
FUNCTION2
 module funct2(w,x,y,z,f2);
input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule

```

```

FUNCTION1

```


![image](https://github.com/user-attachments/assets/b3191905-d66f-4b29-9957-1ff78075505f)

```

FUNCTION2

```

![image](https://github.com/user-attachments/assets/245d9e18-349e-4d8f-be92-a307325d90be)


```

Developed by:VASANTH P
RegisterNumber:24900136

```

**RTL realization**

**Output:**

**RTL**

```

FUNCTION1

```

![image](https://github.com/user-attachments/assets/a08c742f-fe58-4d6c-b989-6047fea08600)

```

FUNCTION2

```

![image](https://github.com/user-attachments/assets/6c73150a-30f7-44de-9314-a555f4ff47f5)

**Timing Diagram**

```

FUNCTION1

```

![image](https://github.com/user-attachments/assets/00829ec2-36de-4b16-a448-d753ec7271a6)

```

FUNCTION2

```

![image](https://github.com/user-attachments/assets/6842c043-610c-4956-957b-ea247590703b)

**Result:**

```

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

```

