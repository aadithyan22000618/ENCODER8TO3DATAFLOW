# ENCODER 8TO3 DATAFLOW MODELLING

# NAME : AADITHYAN R

# REGISTER NUMBER : 212222230001

# AIM:

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED: 

Quartus prime

# THEORY

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/user-attachments/assets/bf3d0233-6f0f-4571-96c7-cbd8f1e72d9a)

# Truth Table

![image](https://github.com/user-attachments/assets/282c932d-d41d-42b9-a0e7-b4a5e8c05031)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/user-attachments/assets/5caf9ebe-f0b1-41e2-9f11-927731c55e67)

# Procedure

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM**

```
NAME : ANTONY ABISHEK
REGISTER NUMBER : 212223240009
module ex05(din,a,b,c);
input [0:7] din;
output a,b,c;
assign a=(din[4]| din[5]|din[6]|din[7]);
assign b=(din[2]| din[3]|din[6]|din[7]);
assign c=(din[1]| din[3]|din[5]|din[7]);
endmodule****
```


# RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling

![image](https://github.com/user-attachments/assets/557d7ac8-6da2-4aab-a782-4a6e49af4c93)

# TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling

 ![image](https://github.com/user-attachments/assets/e8a70541-1694-413d-adba-966718610399)

# RESULTS

implementing Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables executed succesfully.


