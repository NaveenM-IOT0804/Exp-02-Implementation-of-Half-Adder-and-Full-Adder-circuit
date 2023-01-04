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
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: NAVEEN M
RegisterNumber: 22000748
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
![ex2i](https://user-images.githubusercontent.com/117974950/210356925-d5685552-990f-4a58-b174-daee28a446b7.png)
![ex2full](https://user-images.githubusercontent.com/117974950/210357061-72bf13fb-a0cb-4bf7-b5c5-2be955aa96e6.png)

### TIMING DIAGRAM
HALF ADDER
![halfadderwaveform](https://user-images.githubusercontent.com/117974950/210536342-646f63a4-e454-4a4b-b250-b55dcf1c6fc7.png)
FULL ADDER
![fulladderwaveform](https://user-images.githubusercontent.com/117974950/210536387-39004b62-57ec-4028-a0a2-f3572417420c.png)


### TRUTH TABLE 
HALF ADDER
![Half-Adder-Truth-Table-1](https://user-images.githubusercontent.com/117974950/210536185-a3844eb9-248e-45a2-bb87-8e1a67280c0d.jpg)
FULL ADDER
![fulladderturthtable](https://user-images.githubusercontent.com/117974950/210536263-4a502462-8cf7-4101-b921-a885fe85e7e7.png)


### Result: Thus the different digital IC's are studied and the truth table for different logic gates are verified.
