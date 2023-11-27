# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RAHINI.A


RegisterNumber:  23012479



## HALFADDER :

![PROGRAM](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/08775b58-3d33-40f4-b24b-f8a9136fd34f)


## HALF ADDER TRUTH TABLE:

![image](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/90aa02eb-ef8f-42b5-a7cb-70ee086e5ef9)

# RTL VIEW:
![HALF RTL](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/5967f021-e853-49fb-89d9-dd12969b5734)

# TIMING DIAGRAM:
![HALF ADD WAVE](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/1d004437-bbbe-4ac8-a716-d702a987e757)


# FULL ADDER:

![fulladder program](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/0c709b49-be55-43c7-aaf2-78864a232a47)

## FULL ADDER TRUTH TABLE:

![image](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/44c5b1c7-31b1-4ef7-bd7e-d80aba76b4ee)

### RTL:
![fulladder rtl](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/05aabcdd-9a3c-48a3-a38e-b936f4b5f035)

# TIMING DIAGRAM:

![fulladder wave](https://github.com/RahiniAchudhan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145742838/b55696ad-90ad-4de1-928a-71ea35200fc0)

### Result:

Thus the half adder and full adder circuits are designed and the truth table is verified using quartus software.
