/*# find-factorial-using-c*/
/*factorial numbers*/
#include<stdio.h>
#include<conio.h>
int main()
{
int i,n;
long int fact=1;
printf("enter the values:-/n");
scanf("%d", &n);
// factorial seris refers :- !n=n*!(n-1)
for(i=0;i<=n;i++)
{
fact=fact*i;
}
printf("factorial of %d=%d" , n,fact);
}
return 0;
