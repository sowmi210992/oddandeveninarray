#include<stdio.h>
int main()
{
    int n,a[10],even=0,odd=0;

    printf("enter n:");
    scanf("%d",&n);
    for(int i=0;i<n;i++)
    scanf("%d",&a[i]);
    for(int i=0;i<n;i++)
    {
        if(a[i]%2==0)
        even+=a[i];
    
        else
        odd+=a[i];
    
    }
    printf("%d\n",even);
    printf("%d\n",odd);
    return 0;
}
output:
enter n:4
3
6
2
4
even:6 2 4
odd:3
