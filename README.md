# EXP4:FULL ADDER AND SUBTRACTOR
## NAME:MOHAMMED HAMZA
## REGISTRATION NUMBER:24900511

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
![FULL ADDER TRUTH TABLE](https://github.com/user-attachments/assets/4e2192be-d85b-4ae6-a8a1-cbe93d19dc3c)
![FULL SUBTRACTOR TRUTH TABLE](https://github.com/user-attachments/assets/b6600a67-741f-48a6-9c6c-e9a9a1715f69)

**Procedure**

Write the detailed procedure here

**Program:**
![FULL SUBTRACTOR CODE](https://github.com/user-attachments/assets/6c5a52d8-fd5d-4b9d-bea8-fb96da3c6197)
![FULL ADDER CODE](https://github.com/user-attachments/assets/f43b9ca6-2017-4742-91d4-b3e8ddc62213)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![FULL ADDER DIAGRAM](https://github.com/user-attachments/assets/a11a988c-6b0b-4961-bbb1-1aaf98383ee1)
![FULL SUBTRACTOR DIAGRAM](https://github.com/user-attachments/assets/efa07a14-a247-4ce9-ac4d-b0cdfe0782bd)

**Output Timing Waveform**

**Result:**
![FULL SUBTRACTOR WAVEFORM](https://github.com/user-attachments/assets/f51d8a19-4048-49a7-a842-c2541cc644f6)
![FULL ADDER WAVEFORM](https://github.com/user-attachments/assets/a4751680-548c-4501-aa81-d7935758c01a)


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



