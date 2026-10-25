#include<stdio.h>
#include<math.h>

int main(void)
{
    int i=1;
    int a, b , c ;
    double d ;


    while (i==1)
    {
        scanf("%d %d %d" , &a , &b , &c);
        if (a!=0 || b!=0 || c!=0)
        {
            if (a>b && a>c)
            {
                d = sqrt(pow(b,2) + pow(c,2));
                if (d == a)
                {
                    printf("right\n");
                }
                else
                {
                    printf("wrong\n");
                }

            }
            else if (b>a && b>c)
            {
                d = sqrt(pow(a,2) + pow(c,2));
                if (d == b)
                {
                    printf("right\n");
                }
                else
                {
                    printf("wrong\n");
                }

            }
            else if (c>a && c>b)
            {
                d = sqrt(pow(a,2) + pow(b,2));
                if (d == c)
                {
                    printf("right\n");
                }
                else
                {
                    printf("wrong\n");
                }

            }

        }
        else if (a==0 && b==0 && c==0)
        {
            i = 0;

        }
    }


    return 0;
}
