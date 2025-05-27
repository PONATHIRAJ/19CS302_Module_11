# EX 53 C PROGRAM TO CONVERT UPPERCASE TO LOWERCASE WITHOUT 
USING THE INBUILT FUNCTION
## DATE:20/5/2025
## AIM:
To write a C program to remove duplicates in an array.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to convert uppercase to lowercase without using the inbuilt function. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.   

## Program:
```
#include <stdio.h> 
#include <ctype.h> 
#include <string.h> 
 
int main() { 
char str[10]; 
scanf("%s",str); 
int len = strlen(str); 
for (int i = 0; i < len; i++) { 
str[i] = tolower(str[i]); 
} 
printf("%s", str); 
}
```

## Output:
![image](https://github.com/user-attachments/assets/b242ee25-38d9-4ebd-afd3-79d45d7b2e35)
 
RESULT: 
Thus, the program is executed and verified successfully.


## Result:
Thus the program was executed and the output was verified successfully.
