
#include<stdio.h>
int main()
{
    int a,b;
    printf("enter the value of a: ");
    scanf("%d",&a);
    printf("enter the value of b: ");
    scanf("%d",&b);
    if (a>b)
    {
        printf("a is greater then b");

    } 
    else if(a<b)
    {
        printf("b is greater then a");

    }
    else 
    
    {
        printf("a is equal to b");
    }
    return 0;
}
