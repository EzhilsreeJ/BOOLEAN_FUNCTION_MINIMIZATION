# BOOLEAN_FUNCTION_MINIMIZATION

#  AIM:  

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

 # Equipment Required:  

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime  

#  Theory  

  
#  Procedure  

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


#  Program:  
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/  Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: EZHIL SREE J
RegisterNumber:212223230056
 /


 # RTL realization  

![Screenshot 2024-11-15 105609](https://github.com/user-attachments/assets/3702f22c-34c3-4868-b16b-d687cf044f63)

#  Output:  


#  RTL Timing Diagram  
![Screenshot 2024-10-22 113237](https://github.com/user-attachments/assets/5936b03e-6060-4740-a2f4-0c6c3d4dfac8)

# Result:  

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

