# ARM-inspired-Micro-Processor-Design-using-Verilog-HDL
This repository contains Verilog code for my project, ARM-inspired Micro Processor Design using Verilog HDL. It also contains one handwritten report that explains each and every architecture and the design in detail. 


The detailed Handwritten explaination about my 32-bit Processor design is as follows:
![WhatsApp Image 2025-09-03 at 14 11 10_ecff7850](https://github.com/user-attachments/assets/5ee430e5-bfee-41f7-90a2-f3a328086cb1)
![WhatsApp Image 2025-09-03 at 14 11 10_97f558ae](https://github.com/user-attachments/assets/542577a5-4ec0-4fcf-b5b3-0ac02cfdbcc4)
![WhatsApp Image 2025-09-03 at 14 11 11_e4a8c7bc](https://github.com/user-attachments/assets/1b6d6cfd-3f45-4030-8ad0-83fe9e2b8789)
![WhatsApp Image 2025-09-03 at 14 11 11_27986933](https://github.com/user-attachments/assets/b603bc1a-ad61-4985-a6ef-4c63a9483d79)
![WhatsApp Image 2025-09-03 at 14 11 11_5c19404c](https://github.com/user-attachments/assets/afab3b2c-9129-4633-938d-792eefaeb8b7)
![WhatsApp Image 2025-09-03 at 14 11 12_0eafa54c](https://github.com/user-attachments/assets/984b4c30-ace1-4328-87d6-d4b087135347)
![WhatsApp Image 2025-09-03 at 14 11 12_530fe982](https://github.com/user-attachments/assets/b5894833-1b1e-4185-8772-9f1ec3c71712)
![WhatsApp Image 2025-09-03 at 14 11 13_93f02fa9](https://github.com/user-attachments/assets/8da4f5e8-209c-46e7-b2de-70eb0ec6356b)
![WhatsApp Image 2025-09-03 at 14 11 13_fd14ad6c](https://github.com/user-attachments/assets/a9eaef11-6673-4d35-824f-da6f188d28a4)
![WhatsApp Image 2025-09-03 at 14 11 14_1c1cbbc0](https://github.com/user-attachments/assets/c31ec61f-e2db-4b54-b367-c525b095de37)
![WhatsApp Image 2025-09-03 at 14 11 14_bfd7625f](https://github.com/user-attachments/assets/d9c41f53-7f9f-4349-b498-12f635d71f39)
![WhatsApp Image 2025-09-03 at 14 11 14_3e539de9](https://github.com/user-attachments/assets/0adbd102-9d34-4f94-9569-41bc04feebb1)
![WhatsApp Image 2025-09-03 at 14 11 15_fa07f3d6](https://github.com/user-attachments/assets/adc81db5-0b93-483e-ac3d-beb160a619f3)
![WhatsApp Image 2025-09-03 at 14 11 15_7e00b9a7](https://github.com/user-attachments/assets/6ab49c0a-4c23-4ec6-a92d-0b1133ad26e6)
![WhatsApp Image 2025-09-03 at 14 11 16_235af631](https://github.com/user-attachments/assets/7e6b86db-3c1e-418c-a237-682201386529)
![WhatsApp Image 2025-09-03 at 14 11 16_0436dc6c](https://github.com/user-attachments/assets/c4585286-7473-44f5-9af5-05e97abef016)
![WhatsApp Image 2025-09-03 at 14 11 16_f22a01f0](https://github.com/user-attachments/assets/a9e3e905-0437-48b5-a14c-769cf9f0d9f0)
![WhatsApp Image 2025-09-03 at 14 11 17_a622a05e](https://github.com/user-attachments/assets/75096008-693e-4e32-816f-5063fab59c82)
![WhatsApp Image 2025-09-03 at 14 11 17_fda1b496](https://github.com/user-attachments/assets/33e3d40b-0f30-4c55-a2ff-cb4ea67e57cf)
![WhatsApp Image 2025-09-03 at 14 11 18_3ddd5274](https://github.com/user-attachments/assets/0345aab9-a54b-4b24-8ddc-44628e0f91a3)
![WhatsApp Image 2025-09-03 at 14 11 18_657e500b](https://github.com/user-attachments/assets/212c4eb3-0b84-492e-b082-5740e81b30ea)

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





