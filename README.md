#include <stdio.h>

int main(void)
{     
    int a,b,c;
    
    printf("enter a number");
    scanf("%d",&a);
    
    
    b=a%10;
    c=a%100;
    c=c/10;
    a=a/100;
    a=(a*10)+b;
    a=(a*10)+c;
    
    
    printf("%d",a);
    
	return 0;
}

