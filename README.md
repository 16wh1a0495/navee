#include<stdio.h>
int main()
{
  int x,p,y;
  scanf("%d %d",&x,&p);
  printf("%d INR\n",x);
  while(x>=1){
    y=(x*p)/100;
    x=x-y;
    printf("%d INR\n",x);
    if(x==1){
    printf("FREE!!");
    break;
    }
}
return 0;
}
