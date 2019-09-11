#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e,f;
    
    
    printf("enter the a b c of line");
    scanf("%f %f %f ", &a,&b,&c);
    
  printf("center is (%f,%f)", -1*a/2,-1*b/2);
  e=sqrt(((a/2)*(a/2))+((b/2)*(b/2))-c);
  printf ("radius is %f",e);

    
    
	return 0;
}

