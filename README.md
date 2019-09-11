#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e,f, area;
    
    
    printf("enter the four values");
    scanf("%f %f %f %f %f %f ",&a,&b,&c,&d,&e,&f);
    
    printf("the point of intersection is (x,%f)", ((f*a)-(d*c))/((d*b)-(e*a)));
    return 0;
    
    
}

