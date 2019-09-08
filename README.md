#include <stdio.h>

int main(void)
{     
    int a,b;
    
    printf("enter a number");
    scanf("%d",&a);
    b=a;
    a=a%100;
    a=a/10;
    b=b%10;
    printf("%d",a+b);
    
	return 0;
}

