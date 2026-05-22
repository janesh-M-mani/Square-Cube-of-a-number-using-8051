<img width="1919" height="1079" alt="Screenshot 2026-05-20 101355" src="https://github.com/user-attachments/assets/ce0eda02-1bf2-4df7-ba7c-5f1ea12dea96" /># Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV R0, #50H
MOV A, @R0
MOV B, @R0
MUL AB
INC R0
MOV @R0,A
END

```

## OUTPUT

<img width="1919" height="1079" alt="Screenshot 2026-05-20 101355" src="https://github.com/user-attachments/assets/de80ee00-e7e1-4fe3-a047-333d3767fde9" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0, #50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @ RO,A
INC R0
MOV @R0,B
END
```


## OUTPUT

<img width="730" height="1280" alt="WhatsApp Image 2026-05-22 at 9 10 55 PM" src="https://github.com/user-attachments/assets/2f377473-a83b-4bd1-8478-5c278ca05603" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


