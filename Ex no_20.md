# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE: 07-05-2025
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm:
1. Start.
2. Define the required variable.
3. Convert the string to lowercase.
4. Read the value using scanf.
5. Print out the answer.
6. End..

## Program:
```c program
#include <stdio.h>
int main() {
 char str[100];
 int i = 0;
 scanf("%s", str); 
 while (str[i] != '\0') {
 if (str[i] >= 'A' && str[i] <= 'Z') {
 str[i] = str[i] + 32; }
 i++; }
 printf("Lowercase string: %s\n", str);
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/b6db25ec-c9ff-4205-85d6-377e79a1e236)

## Result:
Thus the program was executed and the output was verified successfully.
