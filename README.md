### Register number : 24900880
### Name : Abishek Priyan M
### Experiment 3: IMPLEMENTATION OF HALF ADDER SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**
/
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

![image](https://github.com/user-attachments/assets/d3395e94-060b-4052-b17c-9978433103bb)

![image](https://github.com/user-attachments/assets/525c259f-e97a-4a47-a206-df83d8048021)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![image](https://github.com/user-attachments/assets/cbd9f302-e21e-46ef-b3e6-f20230b89075)


**RTL Schematic**
![image](https://github.com/user-attachments/assets/8a15ffb5-f6ce-45e2-8a63-887b919465df)


![image](https://github.com/user-attachments/assets/284cfbd5-5a49-4e54-85c2-65110296a858)

**Output/TIMING Waveform**
![image](https://github.com/user-attachments/assets/a988fe4d-82e4-40f3-b72b-74de944d44ae)



![image](https://github.com/user-attachments/assets/47fb414a-32e7-4149-aa43-40e5741a9b1f)


**Result:**

Half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming is verified.
