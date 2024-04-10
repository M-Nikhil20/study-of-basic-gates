### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

 Developed by : M Nikhil
 RegisterNumber: 212222230095
 
 ***And Gate***
 ![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/381db9b2-ff2c-4ac0-a5d5-e922eea7dc83)


**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/7478bf39-8d7a-4ec6-940f-fb5ca8661027)


**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/c2c980de-b43d-4b35-9cde-10c68703e126)


**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/742bf349-e5f0-45fd-97c6-9ab7939a6d69)


***Or Gate***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/c4bfcf36-a7a8-415f-8e6b-7ef9da2b127f)


**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/f576f2c6-0bb9-46d7-9272-09b015a92d98)



**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/75bf4af4-676b-483f-9a83-550a6a0c6bd1)



**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/f63d8458-f9bb-4710-a636-85fec2b1a7c6)


***Not Gate***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/68b1f120-941c-45fc-bfc8-b2bf7487b414)



**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/3b5aba8a-5c2f-441e-b5a0-86a895f17dc8)



**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/b6e3aa72-859f-42a4-a305-4989d527b7d7)




**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/bba89a5a-5361-4e22-ad06-b91e7fce6761)



***NAND Gate***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/ec4405ea-ee6d-432b-a1e1-74227e0b7b0d)



**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/c5ac3baf-30c8-45e8-bc3b-39fcd5497bee)




**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/537052ac-4538-47f0-895d-220f93fe8902)




**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/3ad8ffe8-3db7-41e4-ba6f-180fa963eba7)


***NOR GATE***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/117050a2-d459-4faf-b67f-700d17f47d3e)



**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/fbd22757-8d77-4ea3-bf5e-45a9d17bce2e)



**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/fb516e4e-9c09-4e3d-a47f-77fde9ef837f)




**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/226e1e80-c9e7-419f-b953-403813ea28a9)


***EX-OR GATE***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/5a08544a-99ec-44e6-a05a-90545620cee5)



**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/2f7afce2-727e-4da4-832a-90d81670d612)



**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/9b00c9ef-de32-4a58-968c-309597489511)



**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/aafde24c-e820-4e51-bbdc-35b3ff678fef)


***EX-NOR GATE***
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/d8c4a39a-6fe3-4ba1-9ffc-568d6c45b211)



**Logic symbol & Truthtable**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/a8229ad2-675e-44fc-b01a-e4bfa7f92a82)




**RTL realization Output:** 
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/9c2b04a6-0d4d-4edb-8a30-67be459a2ee6)


**RTL**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/fa71c8e9-77dd-431c-802f-3d0ff4c28d74)


**RTL realization Output:**
![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/118707852/6bd6a9ca-3ab7-4318-a809-08091a15291b)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


