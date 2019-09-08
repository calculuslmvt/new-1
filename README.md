#include <stdio.h>

int main(void)
{     
    int a,b;
    
    printf("enter a number");
    scanf("%d",&a);
    
    b=a%10;
    
    printf("%d",a+b);
    
	return 0;
}

