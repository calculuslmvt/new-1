#include <stdio.h>
#include <math.h>

int main(void)
{     
    int a,b,c;
    float semi;
    
    printf("enter the sides of traingle");
    scanf("%d %d %d", &a,&b,&c);
    semi=(a+b+c)/2;
    semi=sqrt(semi*(semi-a)*(semi-b)*(semi-c));
    
    printf("area of the triangle is %.2f",semi);
    
	return 0;
}

