#include<stdio.h>
#include<conio.h>
#include<math.h>
int main()
{ 
int n1,n2;
char op;
printf("what operation u want to perform: +,-,*,/");
scanf("%c",&op);
printf("enter first digit");
scanf("%d",n1);
printf("enter second digit");
scanf("%d",&n2);
if(op=='+'){
  printf("sum is %d \n",n1 + n2);
}
else if(op=='-'){
  printf("subtraction is %d \n",n1-n2);
}
else if(op=='*'){
  printf("multiplication is %d \n", n1*n2);
}
else if(op=='/'){
  printf("division is%d \n",n1/n2);
}
else{
  printf("\n ivaild input");
}
return 0;
}
