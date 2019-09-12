#include <stdio.h>
#include <math.h>

int main()
{     
    
    float a,b,c;
    
    printf("enter a  b c of that line  ");
    
    scanf ("%f %f %f", &a,&b,&c);
    
    printf("the slope is %f \n ",-1*a/b);
    
    if (b==0)
    printf("line is verticle");
    
    
    
        return 0;
}        
    


