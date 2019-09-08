#include <stdio.h>

int main(void)
{     
    int a;
    
    printf("enter a number");
    scanf("%d",&a);
    a=a%100;
    printf("%d",a/10);
    
	return 0;
}

