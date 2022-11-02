#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int num = get_int("Number: ");
    int n = num/5;
    num = num%5;
    while(num%4 > 0 || num-4 <0)
    {
        num = num + 5;
        n = n - 1;
    }
    int m = num/4;
    printf("%i fives and %i fours\n", n, m);
    if(n>=4)
    {
        int j = n/4;
        for(int i = 0; i<j; i++)
        {
            n = n-4;
            m = m+5;
            printf("%i fives and %i fours\n", n, m);
        }
    }
}
