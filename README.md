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
![Screenshot 2024-12-27 202455](https://github.com/user-attachments/assets/c1951b65-5f1f-4ea4-959b-1eb395902fc0)
![Screenshot 2024-12-27 202504](https://github.com/user-attachments/assets/12327e2a-45c3-4514-b5d3-bfecb7c2becf)

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:VAISHNAVI.D RegisterNumber:24900005*/

**RTL Schematic**
![Screenshot 2024-12-27 202515](https://github.com/user-attachments/assets/b248a3bd-00e6-4731-b51d-52feaca93a00)
![Screenshot 2024-12-27 202523](https://github.com/user-attachments/assets/664ca66d-7617-443d-b75a-a53431797460)

**Output/TIMING Waveform**
![Screenshot 2024-12-27 202536](https://github.com/user-attachments/assets/a92d4d3f-a3e0-4b1c-96d6-216d59aed6d7)
![Screenshot 2024-12-27 202546](https://github.com/user-attachments/assets/be30aa5d-898f-4028-8d7f-9c85ecd005d7)

**Result:**
Thus the given logic functions are implemented using Quartus II and their
operations are verified using Verilog programming.
