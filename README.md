#include <stdio.h>
#include <math.h>

int main()
{     
    
    int a,b,c,d,x,i=0;
    
    
    printf("enter a  b c d x \n ");
    
    for (i=0;i<=100;i++)
    { if(i%3==0 || i%5==0)
      continue;
      else if(i%2==0)
      printf("%d ",i);
      else
      continue;
    
    
    }
        return 0;
}        
    


