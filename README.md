# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: alagu nachiyar k
RegisterNumber:212222240006
```
module exp2(A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1=(~A & ~B & ~C & ~D);
assign x2=(A & ~C & ~D);
assign x3=(~B & C& ~D);
assign x4=(~A & B & C & D);
assign x5=(B & ~C & D);
assign F1=x1|x2|x3|x4|x5;
endmodule
```





## Output:

## RTL
![exp 2 diagram](https://github.com/Nachiyarr/Experiment--02-Implementation-of-combinational-logic-/assets/113497340/14771a7d-ad89-4eab-b401-50ee285a7e63)

![exp 22](https://github.com/Nachiyarr/Experiment--02-Implementation-of-combinational-logic-/assets/113497340/ca036a2e-a36b-4b16-8280-120d2e59677f)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
