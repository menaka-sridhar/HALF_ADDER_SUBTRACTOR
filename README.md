# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="555" height="262" alt="Screenshot 2025-11-18 215303" src="https://github.com/user-attachments/assets/c9c6535d-1686-4863-90dc-b82f10865e74" />
<img width="913" height="271" alt="Screenshot 2025-11-18 221919" src="https://github.com/user-attachments/assets/ad11271c-8f31-4b2d-a9c7-daa6ef0a4fb1" />

Developed by:Menaka M S

RegisterNumber:25015729*/

**RTL Schematic**
<img width="1728" height="914" alt="Screenshot 2025-11-18 214912" src="https://github.com/user-attachments/assets/0bc76e35-d60d-4f7d-8e76-7b2afc5f6761" />
<img width="1721" height="974" alt="Screenshot 2025-11-18 221620" src="https://github.com/user-attachments/assets/32f823ee-99a5-4d5c-872a-992a05a79f18" />

**Output/TIMING Waveform**
<img width="1692" height="192" alt="Screenshot 2025-11-18 215137" src="https://github.com/user-attachments/assets/dd6a724f-a102-476a-b147-feb9a7efc600" />
<img width="1688" height="170" alt="Screenshot 2025-11-18 221903" src="https://github.com/user-attachments/assets/85a649d4-8928-47f2-a5ff-72d1e1c1c003" />

**Result:**
Thus,so designed a half adder and half subtractor circuit and verified its truth table in Quartus using Verilog programming.
