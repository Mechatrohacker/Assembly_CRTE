# Assembly_CRTE


This repo include sopme assembly course source codes using nasm compiler.
```
Example compiling:

nasm -f elf Variables.asm
ld -m elf_i386 -o Variables Variables.o
```

DATA REGISTERS:
As complete 32-bit data registers: EAX, EBX, ECX, EDX.
![image](https://user-images.githubusercontent.com/47490071/110324938-93a69f00-800e-11eb-8689-44ec8c2397c2.png)

POINTER REGISTERS:
The pointer registers are 32-bit EIP, ESP, and EBP registers 

![image](https://user-images.githubusercontent.com/47490071/110325666-850cb780-800f-11eb-89c4-fab98e30fac0.png)


INDEX REGISTERS:
The 32-bit index registers, ESI and EDI, and their 16-bit rightmost portions.
![image](https://user-images.githubusercontent.com/47490071/110325749-a077c280-800f-11eb-8879-cd163a3b31e9.png)
