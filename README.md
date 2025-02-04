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
 Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output.

## Logic Diagram
## Procedure:
### step-1

Create a project with required entities.
### step-2

Create a module along with respective file name.
### step-3

Run the respective programs for the given boolean equations.
### step-4

Run the module and get the respective RTL outputs.
### step-5

Create university program(VWF) for getting timing diagram.
### step-6
Give the respective inputs for timing diagram and obtain the results.
## Program:
### Developed by: Marella Dharanesh
### RegisterNumber: 212222240062


Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
### F1:
```python
module dd (a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1 = (~b&~d)|(~a&b&d)|(a&b&~c);
endmodule 
```
### F2:
```python
module dd (w,x,,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = (w&y)|(x&y)|(~y&z);
endmodule
```




## Output:
## F1
### RTL realization:
![de ex-2 1](https://user-images.githubusercontent.com/118707669/234770638-5f66b25a-6cb4-4361-ac6e-ebebd1fa4c27.png)


## Timing Diagram
![de ex-2 1 1](https://user-images.githubusercontent.com/118707669/234770668-4c0f94ae-f57d-461b-b83e-064668914725.png)


## F2:
### RTL realization
![de ex-2 2](https://user-images.githubusercontent.com/118707669/234770764-2b64b733-7e90-4fcb-9a8e-959044075481.png)

### Timing Diagram
![de ex-2 2 1](https://user-images.githubusercontent.com/118707669/234770789-045b6259-656c-40ac-bbf4-a6d1e157cafe.png)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
