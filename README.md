# VSDSquadron-Research-Internship-20th October Cohert
The program is based on the RISC-V architecture and uses open-source tools to teach people about VLSI chip design and RISC-V. The instructor for this internship is Kunal Ghosh Sir.
# Task 1: Install RISC-V toolchain using VDI.Upload snapshot of compiled C code and RISC-V Objdmp on your GitHub repository.
# Description:
The task included downloading a virtual manager and installing the RIS-V toolchain using VDI Write a C code for the sum to n numbers Compile the above code using gcc compiler Compile the above code using the RISC-V simulator
# Installation:
## Oracle Virtual machine

![1](https://github.com/user-attachments/assets/64169e30-52d8-4873-b435-a2cc6f32e320)

## Gedit editor

![image](https://github.com/user-attachments/assets/66139ea1-5360-408a-ab72-cdb1c983f3dd)

# Steps:
1: Open Gedit and write the C code to find the sum of n numbers

![image](https://github.com/user-attachments/assets/de403f84-408e-42ae-816c-2763186d9ad6)

2:Compile the above code using gcc and get the output

![image](https://github.com/user-attachments/assets/86c0898f-4963-4066-8dc4-955c67917a96)

3: Compile and run the same code using the RISC-V Simulator and search for main using the command: "riscv64-unknown-elf-objdump -d sum.o | less" and then type out "/main"

![image](https://github.com/user-attachments/assets/d338286a-0330-4fd9-8333-e339a8425565)

4:Changing it from O1 to Ofast:

![image](https://github.com/user-attachments/assets/b0afa3d2-82f8-44a0-8e89-82772c597c77)

5:Search for main usin the commands: "riscv64-unknown-elf-objdump -d sum.o | less" and then type out "/main"

![image](https://github.com/user-attachments/assets/2280a39a-1636-40e1-96df-d9c09ecf08ae)











