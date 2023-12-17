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

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/3b99e2bd-7ef5-44da-9a58-779a9f10a620)

Full Subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/bbb6c73e-d665-40e0-96b2-f170d88593d7)

## Truthtable

Half subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/8ac5734f-e118-4a27-a702-5df7f1582843)

Full subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/e3d02ded-dd54-4943-b33f-c13e318b68cf)


##  RTL realization

Half Subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/a9e762cc-3bee-4061-8d43-27aa50fd28fe)

Full subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/94fa984a-1125-4bac-8ea8-52594a9646ec)

## Timing diagram 

Half Subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/8213fa43-e98f-4ca5-90c1-5c44ea8f02b8)

Full Subtractor:

![image](https://github.com/yathin07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139841679/2f50ea0c-f218-42f3-b055-df59a295aff9)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
