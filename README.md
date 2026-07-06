//call after referrance ... eigula error finding e ashbe
#include<stdio.h>

void addOne(int *a)
{
    *a=*a+1;
}
int main()

{
    int a=5;
    printf(" before %d",a);
    addOne(&a);
    printf("after %d",a);

return 0;
}

