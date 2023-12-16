# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit
## Name: Manoj M

## Register Number: 23004560

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:Manoj M 
RegisterNumber:23004560  
## Half Adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/bca4af1e-b5d8-400a-874e-d2d315c035f3)

## Full addder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/230d2b75-26de-476d-a073-5eceb15c908b)

## Logic symbol & Truthtable
## Half Adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/3372c8f9-18ca-4dcf-8f04-cde989ba563e)

## Full adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/e4164be3-114b-43dd-a69d-ceb6dced56a4)

## RTL realization
## Half adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/6b081b32-e454-4b99-b6a5-1d2262c26777)

## Full Adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/2b9acfa9-a2c2-4504-b6f0-e37441b6f620)

### TIMING DIAGRAM
## Half Adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/e82a68af-5706-44a2-890f-028d73d22247)

## Full Adder
![image](https://github.com/Manoj0079940/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149366208/24acf375-3e6d-410b-b6cc-f007697ff679)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming
