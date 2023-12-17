# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: YATHIN REDDY T
RegisterNumber:  23007417
*/

## Output:

##Code:

Half Subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/fbec1389-98c7-499a-9288-b082132a38dd)

Full Subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/1b6c570f-3ecf-4e2c-a3fc-5f1f573e0a3f)



## Truthtable

Half subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/bd2fd113-25fe-4e3d-bf7b-c461ec808495)

Full subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/4288ad40-477b-4003-9e08-358c34cb8332)


##  RTL realization

Half subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/975da271-b8c4-4cb5-9128-99d19dd92763)

Full subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/753ec1a5-de38-4580-8536-14a1e7a035e7)

## Timing diagram 

Half Subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/2925b684-4fc0-4f52-8d97-162234fee555)

Full subtractor:

![image](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/b4303cca-d4d1-4bc9-a08f-52b81b85b6f7)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
