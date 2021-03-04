# New-game
#include<stdio.h>
void main()
{
	int n,max,min;
	printf("请输入一组整数:\n");
	scanf("%d",&n);
	max=min=n;
    while(n>0)
	{
		scanf("%d",&n);
		if(max<n) max=n;
		else min=n;
	}
	printf("max=%d min=%d\n",max,min);
}
