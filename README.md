# NAME: PRASIDHA A

# REGISTER NUMBER: 212224230204

# EXPERIMENT-4-IMPLEMENTATION OF FULL ADDER SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULL ADDER and FULL SUBTRACTER**

**FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**FULL SUBTRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTHTABLE**

i) FULL ADDER


![Screenshot 2024-12-26 102849](https://github.com/user-attachments/assets/a380a7b8-c7bb-4e00-8e5a-9ec10b38fa96)


ii) FULL SUBTRACTOR


![Screenshot 2024-12-26 102905](https://github.com/user-attachments/assets/33279232-e7fb-4c07-9b60-6e23a0874cdc)



**PROCEDURE**

1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.


**PROGRAM:**

i) FULL ADDER


![Screenshot 2024-12-26 103629](https://github.com/user-attachments/assets/22095b1e-7f6f-4cfc-8426-e2faa687e627)



ii)FULL SUBTRACTOR


![Screenshot 2024-12-26 104108](https://github.com/user-attachments/assets/21f794bd-6c51-43f9-96bc-24a600b162f5)


**RTL SCHEMATIC DIAGRAM **

i)FULL ADDER


![Screenshot 2024-12-26 104108](https://github.com/user-attachments/assets/21f794bd-6c51-43f9-96bc-24a600b162f5)



ii)FULL SUBTRACTOR


![Screenshot 2024-12-26 104122](https://github.com/user-attachments/assets/18cfb109-b40f-42d2-933d-c415865f68d9)


**OUTPUT TIMING WAVEFORM**

i) FULL ADDER


![Screenshot 2024-12-26 104311](https://github.com/user-attachments/assets/0c33f088-9e69-4395-8ba2-6752448955fb)



ii) FULL SUBTRACTOR


![Screenshot 2024-12-26 104329](https://github.com/user-attachments/assets/c8c34a45-a425-4263-8682-a9b0d8dbefa1)



**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
