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

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: ARJUN N S
RegisterNumber:  23013905
## CODE:
### HALF ADDER:
![Exp3 ha code](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/20f8a07b-da99-457f-b875-af2f1a12e6cc)

### FULL ADDER:
![Exp3 fa code](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/1a103e60-e3a1-432e-9945-9409184265b9)

## TRUTHTABLE:
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/008d9554-da1f-4b02-b61a-98795dbdf696)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/3279ca47-3fb7-470f-b906-76332ca56ea1)

### Output:
### RTL:
### HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/b22d37bd-9b8b-412e-8044-9c4acd052ab6)

### FULL ADDER:
![Exp3 fa RTL diagram](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/748041ab-7387-4ce9-81c4-0769ff1a650d)

### TIMING DIAGRAM:
### HALF ADDER:
![exp3 ha wave](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/877bd4e1-f8e7-4dc9-bbfb-76996b30cb35)

### FULL ADDER:
![exp 3 fa wave](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/0a6cdbe8-510a-42e4-8b8a-26e977217b2b)

### TRUTH TABLE 
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/027d59e1-6f62-41b7-8bcd-735f886fe54a)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/NSArjun/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148233801/e31bb6c1-888d-45d5-9f94-246c642fd452)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
