# To-print-divisor-of-any-number
#include<stdio.h>
#include<math.h>
int main()
{   
    int n,i;
    printf("Please provide a number:\n");
    scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
       if(n%i==0)
        printf("%d ",i);
   }    
    return 0;
}
