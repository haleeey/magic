C program 输出三角形来表示乘法表的两种形态  
===========     
第一形态正三角方法：  
---------------  
 __代码__   
2、代码    
``  
#include <stdio.h>    
int main(void)    
{    
int i,j;    
int sum;    
for (i = 1; i <=9; i++)    
{    
for (j = 1; j<=i; j++)    
{    
printf("%4d",i*j);    
}    
printf("\n");    
}   
``  
第二形态反三角方法：  
---------------  
 __代码__   
2、代码     
``#include <stdio.h>  
int main(void)  
{  
int i,j,k;  
int sum;  
for (i = 1; i <=9; i++)  
{for(k=0;k<=4*i-4;k++)  
printf(" ");  
for (j = i; j<=9; j++)  
{  
printf("%-4d",i*j);  
}  
printf("\n");  
}  
``



