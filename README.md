# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

## Procedure
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
 
# Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: LEKA SRI G
RegisterNumber: 212223100025



### Output:
![286677659-9f293ac6-abd1-477b-b18a-8c2319da2634](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/930d9f78-a5b9-4fa8-98e4-a82f2ec3e51c)
![286677790-a40f7583-fb76-4bea-8d55-fa2368164899](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/68238509-56e1-4439-9d91-2dc86f834604)
![286677955-3b80564e-21d8-4692-bc46-f22e71018b3f](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/383ebf16-c6f9-4787-9fc1-d061e9f9a183)
![286678205-6f83c9ab-dbd3-4645-99f5-1995605e81e3](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/490919ae-e38e-4695-8ade-f193ebd9e0cf)

### RTL
![286678357-67816fb1-f98e-40fd-9cb8-44ef6841162a](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/ccd02b51-4d21-40bb-bed7-9c455af6c7ba)
![286678527-a5d3a624-66c2-4b3c-9b9b-56accc3bbd8c](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/a1636603-dd99-48e0-bd35-cf847d148d70)

### TIMING DIAGRAM
![286678828-d21418bb-2794-48e2-aa9a-e4b3383c868c-1](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/66252d86-e70a-48b7-9798-0724a1079acd)
![286678928-7327c2b9-6b3f-4627-ac8d-cca59887cf8e](https://github.com/lekasri12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037427/e685ed90-a8e4-4485-8311-4ca0cb5213f7)



### TRUTH TABLE 

### Result:
