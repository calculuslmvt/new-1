#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e,f;
    
    
    printf("enter the four values");
    scanf("%f %f %f", &a,&b,&c,&d,&e,&f);

    a=(1/2)*((a*(d-f))-(b*(c-e))+((c*f)-(e*d)));
    printf("area is %f",a);
    
	return 0;
}

