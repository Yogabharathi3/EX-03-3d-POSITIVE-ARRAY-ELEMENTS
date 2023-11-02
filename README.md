# EX-03-3d-POSITIVE-ARRAY-ELEMENTS
## AIM 
To write a C Program to count total number of positive elements in an array. 
## ALGORITHM 
1. Start the program. 
2. Read a variable. 
3. Read the array values n number of times. 
4. If the array value can be divided by 2 then increment count by 1. 
5. Display result. 
6. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
int main() 
{ 
 int n,i,a[10],c=0; 
 scanf("%d",&n); 
 for(i=1;i<=n;i++) 
 { 
 scanf("%d",&a[i]); 
 if(a[i]>0) 
 c++; 
 } 
 printf("count of positive numbers in array: %d",c); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-03-3d-POSITIVE-ARRAY-ELEMENTS/assets/118899387/59c5f379-6a1c-49c1-bad7-f7577f336ad6)
## RESULT 
Thus the program to count total number of positive elements in an array has been 
executed successfully.
