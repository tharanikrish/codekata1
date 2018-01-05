#include<stdio.h>
int main()
{
double number;
printf("Enter a number:");
scanf("%lf",&number);
if(number<=0.0)
{
if(number==0.0)
printf("zero");
else
printf("Negative");
}
else
printf("positive");
return 0;
}
