The Processor designed is a basic processor.
It is capable of performing arithmetic and bitwise operations on two operands at a time.

Characteristics and Features :-

1.  Data bus is of 8 bits
2.  Address bus is of 5 bits
3.  Hence RAM size is 32KB
4.  Two General purpose registers are used - Register A and Register B

Working :-

1.  The operands on which operation is to be performed are first moved into the two general purpose registers.
2.  ALU takes input from these two general purpose registers and gives the output

Buttons and their Functions :-

1.  Operand Input : Enter the Operand
2.  Write Data : Press this push button to write the data into the corresponding location.
3.  INR : It is used to increment the address.
E.g : If current location is 0000 0000 i.e 00H then on pressing INR, current location will become 0000 0001 i.e 01H
4.  Starting Address : Enter the starting address of the operands
5.  Reset to Starting Address : On clicking this, initial address is inputed into the address lines of the RAM.
6.  Read Register : It is used to simultaneously read both A and B registers.
7.  Instruction Select : Enter the Instruction Select opcodes for the desired operation.
8.  Enable Inputs : They enable the particular component.

Follow these steps to use the processor properly!!

1.  Reset to starting address.
2.  Enter the operand
3.  Press Write data
4.  Press INR to go to next location
5.  Enter the operand
6.  Press Write data
7.  Press INR to go the next location.
8.  Repeat it n times, to enter n operands
9.  Now return to the starting address (where the operands are stored) by clicking reset to starting address push button
10.  Enable register A and Click read register button to read the first operand into register A
11.  Then Disable register A.
12.  Click INR button to move to the next operand stored in the consecutive location
13.  Enable register B and Click read register button to read the second operand into register B
14.  Then Disable register B.
15.  Now enter the instruction select opcode and enable ALU ,A and B .
16.  Switch on read register button to simultaneously read both A and B registers so that their contents are fed into the ALU as two operands.
17.  Observe the output of the ALU.

NOTE!!

Negative numbers are represented in 2's complement form.
E.g : Just like 4 bits binary number represents digits from 7 to -8 i.e 2^3-1 to -2^3,
8 bits binary number represents digits from 127 to -128 i.e 2^7-1 to -2^7,
Thus, if MSB is 1, it indicates that the number is negative and is in its 2s complement form.