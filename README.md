# C_Count-Number-of-Digit-From-That-Number

#include<stdio.h>

int count(int No1)
{
    int iCnt=0;

    while(No1!=0)
    {
        No1=No1/10;
        iCnt++;
    }
    return iCnt;
}
int main()
{
    int no1=0;
    int icnt=0;

    printf("Enter the Number");
    scanf("%d",&no1);

   icnt= count(no1);

   printf("Number of Digit are :%d",icnt);

   return 0;

}
