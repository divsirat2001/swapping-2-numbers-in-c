// swapping-2-numbers-in-c
/below is the code in c to swap two numbers without using a temporary variable
#include<stdio.h>
main()
{
int a=1;
int b=2;
printf("Before swap:a=%d,b=%d\n",a,b);
a=a+b;
b=a-b;
a=a-b;
printf("After swap:a=%d,b=%d",a,b);
return 0;
}
