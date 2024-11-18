### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**EQUIMENT REQUIRED:**

Software – Quartus prime 

**THEORY:**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND GATE:**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR GATE:** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT GATE:**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND GATE:**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR GATE:**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**EX-OR GATE:**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**EX-NOR GATE:**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**PROCEDURE:** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**
    
    module de_lg(a, b, c1, c2, c3, c4, c5 , c6, c7);
    input a,b
    output c1, c2, c3, c4, c5, c6, c7;
    assign c1 = ~a;
    assign c2 = a & b;
    assign c3 = a | b;
    assign c4 = ~(a & b);
    assign c5 = ~(a | b);
    assign c6 = a ^ b;
    assign c7 = ~(a ^ b);
    endmodule

### REGISTER NUMBER: 24011393
### NAME: K.DHANUSRI POOJA
 
**LOGIC SYMBOL & TRUTHTABLE:**

![WhatsApp Image 2024-11-18 at 4 15 23 PM](https://github.com/user-attachments/assets/f45fb336-b4cf-4b6c-9884-ed5fbbd11b90)


**RTL REALIZATION OUTPUT:** 

![Screenshot 2024-11-18 162034](https://github.com/user-attachments/assets/bb9acdd7-0423-4d55-89d8-d0a9d6b95d7d)


**RTL WAVEFORM:**

![image](https://github.com/user-attachments/assets/5832ba93-8822-4fa6-b982-eeb3eb6dc4ae)



**RESULT**

Studying and verifing the truth table of logic gate in Quartus II using verilog programming is proved.


