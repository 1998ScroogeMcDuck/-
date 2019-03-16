# -
简单
#include<stdio.h>
void main()
{
	int i,n,sum[i]=1,den=1;
	printf("Please enter the value of N");
		scanf("%d",&n);
	for(i=1;i<=n;i++)
	{
		sum[i]=sum[i]+i-1;
		den=den+sum[i];
	}
	printf("the result is:%d",den);
}
