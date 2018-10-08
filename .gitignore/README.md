/*christie carranza*/
#include <stdio.h>
#include <math.h>

int main()
{
int a,b,c,sum;

printf("Equation is in the form ax^2+bx+c\nEnter a, b, c:\n");
scanf("%i %i %i", &a, &b, &c);

sum=sqrt((b*b)-(4*a*c));

if (((pow(b,2))-(4*a*c))<0)

 printf("No real roots\n");

if (((pow(b,2))-(4*a*c))==0)

 printf("Two equal roots\n");

if (((pow(b,2))-(4*a*c))>0)

 printf("Two distinct roots\n");


return(0);
}


