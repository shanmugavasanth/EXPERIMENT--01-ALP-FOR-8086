# EXPERIMENT--01-ALP-FOR-8086
Name : Shanmuga Vasanth M

Roll no : 212223040191

Date of experiment : 22.08.2024

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

## Addition of 8 bit ALP 
```
org 100h

MOV AX, 5
MOV BX, 3
ADD AX, BX
MOV [0200h], AX
HLT

ret
```

## Output  

![Screenshot (55)](https://github.com/user-attachments/assets/71338e7c-08be-459c-99e0-0e74ee4b0994)

 
## Subtraction of 8 bit numbers  ALP 
 ```
org 100h

MOV AX, 8         
MOV BX, 3         
SUB AX, BX
MOV [0200h], AX
HLT

ret
```

## Output  

![Screenshot (56)](https://github.com/user-attachments/assets/b8446674-6925-4658-9cb3-5f38ab0568a5)


## Multiplication alp 
 ```
org 100h

MOV AX, 2        
MOV BX, 4         
MUL BX
MOV [0200h], AX
HLT               

ret

```

 ## Output  

 ![Screenshot (57)](https://github.com/user-attachments/assets/c26cf818-3643-4885-a0db-c8a0f1b12d3b)


## Division alp 
 ```
org 100h

MOV AX, 8         
MOV BX, 2         
DIV BX            
MOV [0200h], AX   
MOV [0202h], DX   
HLT              

ret
```

## Output  

![Screenshot (58)](https://github.com/user-attachments/assets/019f2ca9-64eb-4d9c-8583-e216c9ff443b)


## Programs for logical operators
## AND
```
org 100h         

MOV AL, 0Fh       
MOV BL, 03h     
AND AL, BL       
MOV [0200h], AL  
HLT               

ret
```

## Output

![Screenshot (59)](https://github.com/user-attachments/assets/712d3240-46b7-4984-b841-14c90de7b7be)


## OR
```
org 100h
          
MOV AL, 0Fh       
MOV BL, 03h       
OR AL, BL         
MOV [0200h], AL   
HLT              

ret
```

## Output

![Screenshot (60)](https://github.com/user-attachments/assets/71c41b0c-a696-4270-96ae-863c28e75de3)


## NOT
```
org 100h

MOV AL, 0Fh      
NOT AL            
MOV [0200h], AL  
HLT
               
ret
```

## Output

![Screenshot (61)](https://github.com/user-attachments/assets/997cafe1-8539-4669-9a34-c1288ec759a0)


## XOR
```
org 100h

MOV AL, 0Fh      
MOV BL, 03h       
XOR AL, BL        
MOV [0200h], AL  
HLT               

ret
```

## Output

![Screenshot (62)](https://github.com/user-attachments/assets/7d21c529-24b6-4879-8003-8950842d6673)


## Result :

Thus, the program was executed on ALP for the fundamental arithmetic and logical operations.
 
