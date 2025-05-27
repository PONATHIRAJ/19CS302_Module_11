EX NO 11D : HACKERRANK PROBLEM. 

C program to input marks of five subjects of a student and calculate total, 
average and percentage of all subjects. How to calculate total, average and 
percentage in C programming. Logic to find total, average and percentage in 
C program. use float data type for all variable.
AIM: 
To write a program to calculate the total,average and percentage. 
 
ALGORITHM: 
1. Start. 
2. Define a variables. 
3. Write a program to calculate the total, average and percentage. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 
 
PROGRAM: 
#include<stdio.h> 
int main() 
{ 
float a,b,c,d,e; 
scanf("%f%f%f%f%f",&a,&b,&c,&d,&e); 
float total,ave; 
float per; 
total=a+b+c+d+e; 
ave=(total)/5; 
per=ave; 
printf("%f\n%f\n%f",total,ave,per); 
}
OUTPUT: 
![image](https://github.com/user-attachments/assets/73864ecf-3777-4cf4-b779-73f66bb5f754)

RESULT: 
Thus, the program is executed and verified successfully.
