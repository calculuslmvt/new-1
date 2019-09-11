#include <stdio.h>
#include <math.h>

int main(void)
{     
    float a,b,c,d,e,f;
    
    
    printf("enter the a b c of line");
    scanf("%f %f %f %f %f ", &a,&b,&c,&d,&e);
    
  a=((a*c)+(b*d)+e)/(sqrt((c*c)+(d*d)));
  printf("distance between line is %f",a);

    
    
	return 0;
}

