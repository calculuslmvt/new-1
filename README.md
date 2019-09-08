#include <stdio.h>

int main(int argc, char **argv)
{int i=0,count=0,b,a;
	printf("enter the number");
    scanf("%d",&a);
    b=a;
    ch:
    for (i;i<123 ;i++)
        {  count++;
            a=a/10;
        
            if (a<1)
             break;
     
          else 
  
           continue ; }
            
            printf("number of digits are %d " , count );
            
           b=b%100;
           if
           b=b/10;
           printf("  \n \n  %d",b);
           getch();
    
	return 0
}
