# My-captain
Swapping of 2 numbers without temporary variable

#include<stdio.h>  
 int main()    
{    
int a,b;     
Scanf("%d%d",&a,&b);
printf("Before swap a=%d b=%d",a,b);      
a=a+b;
b=a-b;
a=a-b;
printf("\nAfter swap a=%d b=%d",a,b);    
return 0;  
}
