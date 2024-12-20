### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**
an 8-to-3 encoder is a combinational circuit that compresses 8 input lines into a 3-bit binary code. It performs the reverse operation of a decoder. Encoders are essential in digital systems for reducing the number of data lines by converting large input data into smaller binary representations.


**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**
![WhatsApp Image 2024-12-10 at 17 43 53_4e5fc9f8](https://github.com/user-attachments/assets/115a853f-e3cf-439d-a6d3-18a31f28dab4)

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**
1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram.


**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:ishwarya  RegisterNumber:24900725
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![WhatsApp Image 2024-12-08 at 14 33 18_7259fa7f](https://github.com/user-attachments/assets/84e15d58-ca42-4f6b-b1c8-b6c098750433)
![WhatsApp Image 2024-12-08 at 14 33 18_109a80d8](https://github.com/user-attachments/assets/fe43e1e0-11fc-4097-ba16-d3d5adaad62d)

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![WhatsApp Image 2024-12-08 at 14 33 18_4d525f54](https://github.com/user-attachments/assets/bfda1b3b-18e0-4cdf-ab24-560386c57361)

**RESULTS**
hence programm encoder 8 to 3 and verification of its truth table in quartus using verilog programming is verified



