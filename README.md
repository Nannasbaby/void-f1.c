#include <stdio.h>
void f1()
{
    int a=1;
    static int b=1;
    a=a*2;
    b=b*2;
    printf("%d\t%d\n",a,b);
}
int main()
{
    f1();
    f1();
    f1();
}
