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

Developed by: VISWA PRAKAASH N J

RegisterNumber:  23001661

Code:

Half Adder:

![Exp3 ha code](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/12d2dc7a-d6d2-41e2-bb5b-3d9217538235)

Full Adder:

![Exp3 fa code](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/a601fffb-682f-46c6-a27c-f1c13209ae60)

Truth table:

Hall  Adder:

![Exp3 truthtable (ha)](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/8b222787-5e88-4167-aa03-8435267845e7)

Full  Adder:

![Exp3 truthtable (fa)](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/89080ad3-0ce5-4d59-95f4-44661b0344fb)


RTL Diagram:

Half Adder:

![Exp3 ha RTL diagram](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/dff947e9-d1f6-4636-b1e4-bdd75747e95f)

Full Adder:

![Exp3 fa RTL diagram](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/060423e5-080f-4c22-888f-59e10926eca0)


### Output:

Half Adder:

![halfadder-wave](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/51c13bfc-7725-42b8-9076-3f6f6e8f3c65)

Full Adder:

![Exp3 fa wave](https://github.com/ViswaPrakaashNJ/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150996664/05945484-2af0-451a-a51c-84a1d346288d)


### Result:

Thus the half adder and full adder circuit are designed and the truth table for half adder and full
adder are verified.
