# Module-5 Day-5 SEB
## AIM:
To write a c program to find factorial of the number  '10' using pointer.

## For example:

## Program:
```c
#include<stdio.h>
int main(){
    int n;
    int*p=&n;
    scanf("%d",p);
    int fact=1;
    int i=1;
    while(i<=*p){
        fact*=i;
        i++;
    }
    printf("Factorial of entered number is : %d",fact);
    return 0;
}
```
## Result:
