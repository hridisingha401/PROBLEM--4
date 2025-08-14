#include<stdio.h>
int main()
{
    int K,M;
    scanf("%d %d",&K,&M);

    if (M%K == 0)
    {
        printf ("0");
    }
    else
    {
        printf ("%d",K%(M%K));
    }
    return 0;

}
