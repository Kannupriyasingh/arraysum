# arraysum
#include<stdio.h>
#include<stdlib.h>
int Arraysum( int Myarray[],int size)
{
    int sum=0;
    for (int i=0; i < size ;i++)
    {
        ///sum = sum + Myarray[i]
        sum += Myarray[i];
    }
    return sum;

}
int main()
{
    int MyArraySum[6]={20,30,40,50,60,70};
    int sum_of_array=Arraysum(MyArraySum,6);
    printf("array sum=%d",sum_of_array);
}
