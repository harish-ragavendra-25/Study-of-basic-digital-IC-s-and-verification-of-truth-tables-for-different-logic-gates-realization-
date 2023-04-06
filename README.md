
7) Ex-NOR gate
The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.

Y= A⊕B

Procedure
Connect the supply (+5V) to the circuit
Switch ON the main switch
Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.
If the output is 1, then the bulb glows.
Check all the gates following the same procedure.



 ## Program:
```
module gates(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a);
xor(y4,a,b);
xnor(y5,a,b);
nand(y6,a,b);
nor(y7,a,b);
endmodule
```
Program to verify the truth table in quartus for the basic logic gates using Verilog programming.
## Developed by: PRAVEEN BV
## RegisterNumber:  212222100036
## Logic symbol & Truthtable
![truthtable - Copy](https://user-images.githubusercontent.com/114852180/230293657-3a7cb95f-5446-408f-aa19-70314bb948ea.png)

## Output:
![waveformex1](https://user-images.githubusercontent.com/114852180/230293525-67866e32-465f-499b-89b4-1a7d733c62d8.png)

## WAVEFORM
![ex1digitalgates](https://user-images.githubusercontent.com/114852180/230293428-c3f7abde-b2ff-4c7a-a928-525d018b4204.png)


Result:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
