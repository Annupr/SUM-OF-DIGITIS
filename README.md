# SUM-OF-DIGITIS
Here is the program to find sum of digits
#include<stdio.h>
int main()
{
	int num,sum=0,temp,n;
	printf("\nEnter a number:");
	scanf("%d",&num);
	n=num;
	while(num!=0)
	{
		temp=num%10;
		num=num/10;
		sum=sum+temp;
	}
	
		printf("sum of digit of %d is %d",n,sum);
		
		return 0;
}
