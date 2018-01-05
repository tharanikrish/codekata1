#include<stdio.h>
int main()
{
int a;
printf("enter your number:");
scanf("%d",a);
printf("the number is: %d",a);
if(a<0)
{
printf("the number is negative");
}
elseif(a>0)
{
printf("positive");
else
printf("zero");
}
}
