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

![ex4 truth table](https://github.com/user-attachments/assets/988bcdc6-d89e-4f4d-9675-52f162ec97b0)

![Screenshot 2024-12-04 210024](https://github.com/user-attachments/assets/e41504aa-f432-4867-9d86-67cea2f10193)



**Procedure**

1.Type the program in Quartus software
2.Compile and run the program
3.Generate the RTL schematic and save the logic diagram
4.create nodes for inputs and outputs to generate the timing diagram
5.for different input combinations generate the timing diagram

**Program:**

![ex4 program](https://github.com/user-attachments/assets/d519ffa3-2c21-4dc4-99ca-f1cc7e2d7248)


![ex42 program](https://github.com/user-attachments/assets/f0be13fa-0c61-413c-8e31-29de3faa6f77)



**RTL Schematic**

![Screenshot 2024-12-04 202107](https://github.com/user-attachments/assets/b8b79c5f-a700-43ae-9890-025586c61121)


![ex42 logic](https://github.com/user-attachments/assets/0b426be0-c7c7-4f69-bb42-4b8a6ff07d76)


**Output Timing Waveform**

![Screenshot 2024-12-04 201702](https://github.com/user-attachments/assets/48ba4141-25e0-44a8-96d6-a158802fb8fb)


![WhatsApp Image 2024-12-04 at 20 43 59_c0efcfd5](https://github.com/user-attachments/assets/c58f7940-779c-404a-bbfe-65f858760a24)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



