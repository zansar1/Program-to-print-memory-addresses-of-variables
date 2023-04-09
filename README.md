# Program-to-print-memory-addresses-of-variables

This program demonstrates how to print the memory addresses of variables in C using the & (address-of) operator.

The program initializes a char variable and an int variable, and prints their addresses as well as the addresses of the variables immediately preceding and following them in memory.
Code Explanation

    Declare a char variable charvar and initialize it to the null character \0.
    Print the memory address of charvar using the %p format specifier.
    Print the memory address of the variable immediately preceding charvar in memory by subtracting 1 from the address of charvar.
    Print the memory address of the variable immediately following charvar in memory by adding 1 to the address of charvar.
    Declare an int variable intvar and initialize it to 1.
    Print the memory address of intvar using the %p format specifier.
    Print the memory address of the variable immediately preceding intvar in memory by subtracting 1 from the address of intvar.
    Print the memory address of the variable immediately following intvar in memory by adding 1 to the address of intvar.

The output of the program should show the memory addresses of the variables and their neighbors in memory.

Note: The actual memory addresses may vary depending on the system and compiler used to run the program.
Output

Example output of the program might look like this:

    address of charvar = 0x7fffa0fccebf
    address of charvar - 1 = 0x7fffa0fcccbe
    address of charvar + 1 = 0x7fffa0fccec0
    address of intvar = 0x7fffa0fcccac
    address of intvar - 1 = 0x7fffa0fccc98
    address of intvar + 1 = 0x7fffa0fcccc0
