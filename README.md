# EX - 05 Program to Check Whether 2150 is a Leap Year or Common Year Using Conditional Operator

## AIM:
To write a C program to check whether the year 2150 is a leap year or a common year using the conditional (ternary) operator.

## ALGORITHM:
1. Start
2. Declare an integer variable year.
3. Assign year = 2150.
4. Apply the leap year condition:
5. A year is a leap year if it is divisible by 400, or if it is divisible by 4 but not by 100.
6. Use a ternary operator to check the condition and print whether it is a Leap Year or Common Year.
7. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    int year;
    int leap;
    printf("Enter the year: ");
    scanf("%d",&year);
    leap = (year%4==0)? 1 : 2;
    if(leap == 1)
    {
        printf("LEAP YEAR");
    }
    else
    {
        printf("COMMON YEAR");
    }
    return 0;
}
```

## OUTPUT:

<img width="663" height="126" alt="image" src="https://github.com/user-attachments/assets/018897ab-e1ee-4a16-9f38-1f4c4ba8ac2b" />

## RESULT:
The program successfully checks whether the year 2150 is a leap year or a common year using the conditional (ternary) operator, and displays the correct result.
