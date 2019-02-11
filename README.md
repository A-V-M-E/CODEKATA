#include <stdio.h>
 
int main(void) {
	int n;
	printf("INPUT");
	scanf("%d",&n);
	if(n%2==0)
	{
		printf("POSITIVE");
	}
	else
	{
		printf("NEGATIVE");
	}
	return 0;
}
