# c_training
c programs on sum of 
#include<stdio.h>
int main()
{
    int a[1000],i,n,sum;  
 
     printf("Enter size of array: ");
    scanf("%d",&n);
 
     printf("Enter %d elements in the array : ", n);
    for(i=0;i<n;i++)
    {
        scanf("%d", &a[i]);
    }
 
    printf("\nElements in array are: ");
    for(i=0;i<n;i++)
 
    {
        sum=sum+a[i];
        printf("\n%d", a[i]);
       
    }
     printf("\nthe sum of elemts in array are %d",sum);
    return  0;
