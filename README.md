# ARM-inspired-Micro-Processor-Design-using-Verilog-HDL
This repository contains Verilog code for my project, ARM-inspired Micro Processor Design using Verilog HDL. It also contains one handwritten report that explains each and every architecture and the design in detail. 
This readme file mostly contains information about the testing.

CPUs Instruction set
Our designed CPU can handle the following commands.

Data Processing: ADD SUB AND ORR

Memory Operation: STR and LDR

Branch: B

Also, cover all the conditional mnemonics from ARM LRM, as shown in the snapshot below.
<img width="1170" height="1042" alt="image" src="https://github.com/user-attachments/assets/638f49e8-6672-40d1-8218-0f313511cb0c" />

To test a CPU working we need to have an extensive code which can examine each and every instruction covered in this CPU design , and then if that code is being executed by our CPU with the required final result we can say that CPU passed the initial test

To test our design, we have taken reference test Code from Digital Design and Computer Architecture ARM edition by Harris.

Test Code :
<img width="644" height="666" alt="image" src="https://github.com/user-attachments/assets/011de9a0-7282-4bce-b85f-75402ea84501" />
imem.v : instruction memory source this codes in hexadecimal format .

testbench.sv : Check if we are getting mem[84]==7 or not, which is the final expected outcome of this test code .





