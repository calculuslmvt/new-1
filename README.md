#include <stdio.h>
#include <math.h>

int main()
{     
    
    float a,b,c,d,x,i=0;
    
    
    printf("enter a  b c d x \n ");
    
    scanf ("%f %f %f %f %f", &a,&b,&c,&d,&x);
    
    if (a==x)
    {i++;
    ch1:
     if(b==x)
     i++;
     ch2:
     if (c==x)
    i++;
    
     if(d==x)
     ch3:
     i++;
    }
    else if(b==x)
    goto ch1;
    else if(c==x)
    goto ch2;
    else if (d==x)
    goto ch3;
    printf("%f",i);
    

        return 0;
}        
    


