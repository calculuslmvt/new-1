#include <stdio.h>
#include <math.h>

int main()
{     
    
    float a,b,c,d;
    
    printf("enter a  b c of quadratic eqn\n ");
    
    scanf ("%f %f %f", &a,&b,&c);
    
    d = (b*b)-(4*a*c);
    if (d>0)
    printf( "roots are %f , %f ", ((-1*b)-sqrt(d))/(2*a),((-1*b)+sqrt(d))/(2*a) );
    else if (d==0)
    printf("roots are %f", (-1*b)/(2*a));
    else
    printf("the real part is %f and the imaginary part is +and - %f ",-1*b/2*a,sqrt(-d)/2*a);
    

        return 0;
}        
    


