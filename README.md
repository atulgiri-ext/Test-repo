#include <stdio.h>


int main(void)
{
    int array = 0;
    int counter = 0;
    
    do
    {
        counter ++;
        
        if (counter == 45)
        {
            array = 10;
            (void)printf(" %d and array : %d\n", counter, array);
        }
        (void)printf(" %d and array : %d\n", counter, array);
            
    }while((0 == array) && (25 >= counter));
}
