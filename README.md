# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here


**Program(a):**
![exp4 code](https://github.com/user-attachments/assets/8562a1f9-1bb6-4ac2-8fa1-a93a3c7f7017)
**Program(b):**
![exp4b code](https://github.com/user-attachments/assets/07dfa89e-87c2-4d85-bbe0-41fc58243d12)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic(a)**
![exp4 RTL](https://github.com/user-attachments/assets/566b4630-c520-4908-b17c-0d36a93fd27d)
**RTL Schematic(b)**
![exp4b RTL](https://github.com/user-attachments/assets/2cb92b77-6395-4450-9e1d-8171d056ad73)


**Output Timing Waveform(a)**
![exp4 op](https://github.com/user-attachments/assets/66df5d11-d2b7-4a05-9c67-0a036c40c240)
**Output Timing Waveform(b)**
![exp4b op](https://github.com/user-attachments/assets/d14513d9-1468-4326-aee9-490a284946a4)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



