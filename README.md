#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e;
    
    
    printf("enter the four values");
    scanf("%f %f %f %f", &a,&b,&c,&d);
    e=sqrt(((a-c)*(a-c))+((b-d)*(b-d)));
    
    printf("the length is %f",e);
    
	return 0;
}

