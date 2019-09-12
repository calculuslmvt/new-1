#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e,f,g,h,r,t;
    
    
    printf("enter the values");
    scanf("%f %f %f %f %f %f %f %f",&a,&b,&c,&d,&e,&f,&g,&h);
    
   t= (-1*((a*(e/2))+(b*(f/2))+(c*(g/2))-d))/(sqrt((a*a)+(b*b)+(c*c)));
   r= sqrt((e*e/4)+(f*f/4)+(g*g/4)-h);
   printf("radius of the circle formed is %f", sqrt((r*r)-(t*t)));
    return 0;
    
    
}

