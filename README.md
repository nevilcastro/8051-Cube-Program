# 8051-Cube-Program
# 3.Square-cube-of-given-number
  8051 Square Program
# AIM
 To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

# APPARATUS REQUIRED
  1. Personal computer
  2. Keil μVision IDE
# ALGORITHM
  1. Enter the Assembly language program.
  2. Provide the input value to Port 0 (P0).
  3. Execute the program.
  4. The output square value is stored in Port 2 (P2).
# PROGRAM
```
ORG 0000H
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END
```
# OUTPUT
<img width="885" height="207" alt="image" src="https://github.com/user-attachments/assets/5c78d60d-0654-4e20-9beb-0e360c8639aa" />

# Result
 Thus, the cube of the given data is calculated using 8051 Keil.
