### Register number : 24007066
### Name : lakshmen prashanth R
### Experiment 3: IMPLEMENTATION OF HALF ADDER SUBTRACTOR


**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**:
/
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**:

![image](https://github.com/user-attachments/assets/d3395e94-060b-4052-b17c-9978433103bb)

![image](https://github.com/user-attachments/assets/525c259f-e97a-4a47-a206-df83d8048021)



**Procedure**:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![Screenshot 2025-01-07 124652](https://github.com/user-attachments/assets/39f717f6-9953-49dc-a9f3-7f55b7ab8e72)


**RTL Schematic**:

![Screenshot 2025-01-07 124737](https://github.com/user-attachments/assets/d6402463-d391-4401-8fab-ead6bb7f0f8b)

![Screenshot 2025-01-07 124801](https://github.com/user-attachments/assets/8b522a15-3ae1-48bc-a802-8857d1568dd4)

**Output/TIMING Waveform**:

![Screenshot 2025-01-07 124916](https://github.com/user-attachments/assets/50a14612-07e8-49e3-a031-50474370e8be)

![Screenshot 2025-01-07 125054](https://github.com/user-attachments/assets/c3b1ef93-83fd-41a4-8eed-71ec45382a45)

**Result**:

Half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming is verified.


