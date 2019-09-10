#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e;
    
    
    printf("enter the four values");
    scanf("%f %f %f", &a,&b,&c);
    d=((c*c)+(b*b)-(a*a))/(2*a*b);
    printf("value in degree is  %.2f  in radian is %f ",acos(d)*(180/3.14159),acos(d)); 
    
	return 0;
}

