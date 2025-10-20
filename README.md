# Program-6-b
## C-Module 6
## EX_NO-06)b)-Dynamic Memory Allocation
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to Print 'Printer' using malloc() and free()
## ALGORITHM:
1. Start the program.
2. Declare a character pointer to store a dynamically allocated string.
3. Allocate memory for 10 characters using malloc and assign it to the pointer.
4. Copy the string "Printer" into the allocated memory using strcpy.
5. Print the string using printf.
6. Free the allocated memory using free.
7. End the program.

## PROGRAM:
```
#include<stdio.h>
#include<stdlib.h>
#include<string.h>
int main()
{
    char *str;
    str=(char*)malloc(10*sizeof(char));
    strcpy(str,"Printer");
    printf("%s",str);
    free(str);
}
```
## OUTPUT:
<img width="851" height="235" alt="Screenshot 2025-10-20 093735" src="https://github.com/user-attachments/assets/d8e21347-bf62-4097-8c7a-23f0caf30e97" />

## RESULT:
Thus the program to Print 'Printer' using malloc() and free() has been executed successfully
