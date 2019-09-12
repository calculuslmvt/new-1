#include <stdio.h>
#include <math.h>

int main()
{     
    
    float a,b,c,d;
    
    printf("enter a  b c \n ");
    
    scanf ("%f %f %f", &a,&b,&c);
    
    if (a==b)
    printf("%d",c);
    else if(a==c)
    printf("%d",b);
    else if (b==c)
    printf("%d",a);
    else 
    printf("invalid input");

        return 0;
}        
    


