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
![WhatsApp Image 2024-11-28 at 18 48 50_e119dc1e](https://github.com/user-attachments/assets/1ab603a4-175a-48fa-9b30-08ef68d43e33)
![WhatsApp Image 2024-11-28 at 18 49 01_3e2e7f2d](https://github.com/user-attachments/assets/50b26818-22de-4413-adcd-df8ca17a7a8c)

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
![Screenshot 2024-11-28 190227](https://github.com/user-attachments/assets/55a54b87-3728-47a4-942b-f96ff359819a)
![Screenshot 2024-11-28 191032](https://github.com/user-attachments/assets/90d39dc1-8b6a-404a-9a06-dc9b91329e83)

**RTL Schematic**

![Screenshot 2024-11-28 190245](https://github.com/user-attachments/assets/dd6820af-8480-4f03-b912-66d708461951)

![Screenshot 2024-11-28 191057](https://github.com/user-attachments/assets/1398bfc7-6176-4f0d-ae1d-1a16117bb9ca)

**Output Timing Waveform**

![Screenshot 2024-11-28 190528](https://github.com/user-attachments/assets/f713d2e3-2c2e-45fa-a8f2-40b450414745)

![Screenshot 2024-11-28 191231](https://github.com/user-attachments/assets/5bd537b1-9e18-4570-b4a2-c098e475c317)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



