# Interchange
#include<stdio.h>
void main(){
int n,m,temp;
printf("enter two numbers :-");
scanf("%d %d",&n, &m);
temp=n;
n=m;
m=temp;
printf("the interchange number is %d %d",n,m);

}


