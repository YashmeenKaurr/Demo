#include<stdio.h>
int main(){
    int a,b,c;
    int avg;
    printf("enter marks:\n");
    scanf("%d%d%d", &a,&b,&c);
    avg=(a+b+c)/3;
    printf("\naverage of marks is:%d\n", avg);
    if (avg<=100 && avg>=80){
        printf("A+\n");}
    else if (avg<=79 && avg>=70){
        printf("A\n");
    }
    else if (avg<=69 && avg>=60){
        printf("B+\n");
    }
    else if (avg<=59 && avg>=50){
        printf("B\n");
    }
    else if (avg<=49 && avg>=40){
        printf("C\n");
    }
    else{
        printf("Fail\n");
    }
    }
