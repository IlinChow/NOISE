#include<stdio.h>
#include<math.h>
void main()
{
int n,m,i,j,sum=0,k;
while(~scanf("%d%d",&n,&m))
{    k=0;
     for(i=1;i<=n/m;i++)
	 {    sum=0;
	 if(i>1) printf(" ");
		for(j=1;j<=m;j++)
		{
			k=k+2;
			sum+=k;
		}
		printf("%d",sum/m);
	 }
	 if(n%m){
		 sum=0;
      for(j=1;j<=n-n/m*m;j++)
	  {
		   k=k+2;
		   sum+=k;
	  }
	  printf(" %d",sum/(j-1));}
	 printf("\n");
}
}
