#include<stdio.h>
#include<conio.h>
void main()
{
int i,n,sum;
printf("enter the count of n natural numbers to be summed");
scanf("%d",&n);
sum=0;
for(i=1;i<n;i++)
{
sum=sum+i;
}
printf("sum of %d natural numbers is %d",n,sum);
getch();
}

