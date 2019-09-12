#include <stdio.h>
#include <math.h>

int main()
{     
    
    int a,b,c;
    
    printf("enter three sides of triangle ");
    
    scanf ("%d %d %d",& a,&b,&c);
    
    if ((a*a)==((b*b)+(c*c)))
    printf("A is 90 degrees");
    else 
    printf ("a is not  90 degree");
    
        return 0;
}        
    


