//linear search
#include <stdio.h>
int main()
{
    int i=0,val;
    int a[]={72,11,13,90,24};
    int n=5;
    printf("Enter the value to search to search:");
    scanf("%d",&val);
    for(i=0;i<n;i++)
    {
        if(a[i]==val)
        {
            printf("element is found at position %d",i);
            break;
        }
    }
    if(i==n)
    {
        printf("Element is not present");
     }
    return 0;
}
