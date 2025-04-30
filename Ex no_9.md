# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:30/04/25
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start. 
2. Define a variables a.
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.  

## Program:
```
#include <stdio.h>
int main()
{
    int a,b,c;
    scanf("%d%d",&a,&b);
    c=0;
    for(int i=a;i<=b;i++)
    {
        if(i%2!=0)
        c=c+i;
        
    }
    printf("%d",c);
    
}
```

## Output:
![image](https://github.com/user-attachments/assets/9ca6021c-c4b6-4db3-a4ae-4b470c81e62f)

## Result:
Thus the program was executed and the output was verified successfully.
