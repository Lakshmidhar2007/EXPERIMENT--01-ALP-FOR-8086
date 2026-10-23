# EXPERIMENT--01-ALP-FOR-8086

Name : LAKSHMIDHAR N

Roll no : 212224230138

Date of experiment : 23/10/2026





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```asm
ORG 100H

MOV AX, 0005H
MOV BX, 0003H
ADD AX, BX
MOV [1200H], AX
HLT
```


## Output  

<img width="1190" height="673" alt="image" src="https://github.com/user-attachments/assets/4af5e265-2283-4152-b8d4-6e5b262dc740" />

 
## Subtraction   of 8 bit numbers  ALP 

```asm
ORG 100H

MOV AX, 0009H
MOV BX, 0004H
SUB AX, BX
MOV [1200H], AX
HLT
```
 
## Output  

<img width="1597" height="696" alt="image" src="https://github.com/user-attachments/assets/5509ea88-2d52-4e91-90c1-57b019d69e6b" />


## Multiplication alp 

```asm
ORG 100H

MOV AX, 0005H
MOV BX, 0003H
MUL BX
MOV [1200H], AX
HLT
```

## Output  

<img width="1567" height="666" alt="image" src="https://github.com/user-attachments/assets/b63e6f6b-70d7-42fb-9bc2-00c186db864f" />


## Division alp 

```asm
ORG 100H

MOV AX, 0014H
MOV BX, 0004H
MOV DX, 0000H
DIV BX
MOV [1200H], AX
HLT
```

## Output  

<img width="1561" height="668" alt="image" src="https://github.com/user-attachments/assets/baefb5e5-fb99-4afe-a860-2002a1d9fc47" />


## AND Operation of 8 bit numbers ALP

```asm
ORG 100H

MOV AX, 000CH
MOV BX, 000AH
AND AX, BX
MOV [1200H], AX
HLT
```

## Output



## OR Operation of 8 bit numbers ALP

## Output

## NOT Operation of 8 bit numbers ALP

## Output


## Result :
 








