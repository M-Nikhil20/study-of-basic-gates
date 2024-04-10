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

 Developed by:ABISHAI KC RegisterNumber: 212223240002
 
 ***And Gate***
 
 ![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/20ea9eaa-bd4f-4377-9983-39448af90e87)
 
**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/25a88e3d-2ffd-47ca-bb39-af224af9060e)


**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/a1b4406c-c4b6-4c0b-8b7a-b6126a97591a)

**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/44af20d0-8076-4bf0-974c-9623f01091a2)

***Or Gate***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/4ba26ab8-960d-4524-8475-26db2716dc35)

**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/aa98ba40-3ca3-4baf-bbbd-e3a7398159a9)


**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/cfc2c12d-b798-4f7d-83ab-4af9150ff5da)


**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/9c8c4ca9-9796-4be0-925f-06c6548a63a1)

***Not Gate***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/160398dc-2ecc-4fd8-965e-e938ee61bb1e)


**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/c2b9713a-020a-4328-915e-0dc9d50eeee3)


**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/16bc1aba-38b3-473d-b375-a4bf6e05a71a)



**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/2cbb161e-a3b7-4d55-b694-0703ba0777a5)


***NAND Gate***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/147db95f-0490-42f3-9b07-9daed47e7ce5)


**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/df14dfba-370d-42e4-a0c9-62d97774d60a)



**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/48572c81-8ab5-4138-9cf9-08e1949038a1)



**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/7e0b6176-6b79-4d61-ad77-02979eb3b46e)

***NOR GATE***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/5d351dae-2a91-4898-9d91-248e62063143)


**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/0d6bbca1-d904-49bd-b3ab-07cc05956d9c)


**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/ca42f1bc-dfd6-4199-9849-dbc0929c56d4)



**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/0d4eb4ae-016d-468c-b52d-597e8d914291)

***EX-OR GATE***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/ad9ac5d6-6c87-4e30-baa2-c9fefdddf11e)


**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/f2d4da48-9d25-42bd-a011-a23d3be4f396)


**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/1029a4ad-13d2-4d61-992a-ae7e82d10329)


**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/16d97f70-f0e6-4408-9bee-02cd821e2339)

***EX-NOR GATE***

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/91a00505-14db-4e4e-87ee-7ac8c3f828da)


**Logic symbol & Truthtable**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/5da6033c-7745-43fb-95a2-1e53b678cac5)



**RTL realization Output:** 

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/c8cf8cad-414e-4f91-9172-7f3168bced2c)

**RTL**

![image](https://github.com/M-Nikhil20/study-of-basic-gates/assets/139335314/955cc193-153c-4e79-a530-7cb3a0fadccb)



**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


