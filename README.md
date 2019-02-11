#include <stdio.h>
 
int main() 
{
	int n;
	printf("INPUT:");
	scanf("%d",&n);
	if(n<0)
	{
	printf("Output \nNEGATIVE");
	}
	if(n>0)
	{
	printf("Output \nPOSITIVE");
	}
	if(n==0)
	{
	printf("Output \nZERO");
	}
	return 0;
}
