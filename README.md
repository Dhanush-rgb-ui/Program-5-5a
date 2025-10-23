# Module-5 Day-1 SEB
## AIM:
To write a c program to find factorial of the number  '10' using pointer.

## For example:
<img width="395" height="72" alt="image" src="https://github.com/user-attachments/assets/c1283d07-83ea-48bd-b8d0-cf8dc3e3bf63" />

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
<img width="803" height="108" alt="image" src="https://github.com/user-attachments/assets/f13533f5-f3a5-4c79-a835-8fe21c25afe9" />
