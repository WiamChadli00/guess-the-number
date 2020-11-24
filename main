#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
    const int MIN=1,MAX=100;
    int nombremystere;
    int ans=0;
    int compteur=0;
    srand(time(NULL));
    nombremystere = (rand() % (MAX - MIN + 1))+ MIN;
    printf("guess the number!\n \n choose a number between 1 and 100 \n \n try to guess the number in under 10 attempts , yallah byn liya ");
    do
    {
        scanf("%d",&ans);
        if (ans>nombremystere)
        {
            printf("hbet chuiya");
        }
        else
        {
            printf("zid chuiya");
        }
        compteur++;

    }while(nombremystere!=ans);
    if(compteur<10)
    {
        printf("\n \n \n Naaaaaaaaaadi a Canadi");

    }
    else
    {
        printf("\n\nHya hadik , Yallah 3la slamtk \n \n");
    }
    printf(" \njbtiha f %d dial d9at",compteur);

    return 0;
}
