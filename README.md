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

**Program:**
##FULL ADDER
<img width="1009" height="272" alt="Screenshot 2025-12-06 225353" src="https://github.com/user-attachments/assets/a33ccc2c-b32b-4731-afa2-5f5e2d48463f" />
## FULL SUBTRACTOR
<img width="1005" height="328" alt="Screenshot 2025-12-06 225418" src="https://github.com/user-attachments/assets/95e46269-fd03-4d31-986b-33161ef6c96c" />


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:PON SARAVANA PANDIAN B
RegisterNumber:25005762
*/

**RTL Schematic**
##FULL ADDER
<img width="1023" height="579" alt="Screenshot 2025-12-06 225440" src="https://github.com/user-attachments/assets/cfb8929d-67a3-496f-81ab-7afb4d2ff205" />
##FULL SUBTRACTOR
<img width="1027" height="504" alt="Screenshot 2025-12-06 225459" src="https://github.com/user-attachments/assets/d29803af-f504-4ce1-932d-9cf17948d8f0" />

**Output Timing Waveform**
##FULL ADDER
<img width="1022" height="281" alt="Screenshot 2025-12-06 225518" src="https://github.com/user-attachments/assets/407d2eea-2fd8-4132-b26b-60e7f43de235" />
##FULL SUBTRACTOR
<img width="983" height="255" alt="Screenshot 2025-12-06 225534" src="https://github.com/user-attachments/assets/cb005f0c-0ffb-4a97-b4cb-2e8c2b4ce70e" />


**Result:**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



