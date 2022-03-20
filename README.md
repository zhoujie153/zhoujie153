#include<stdio.h>
#define size 100
int main()
{
	char a[size];
	char b[size];
	int i=0,j=0,c=0;
	printf("输入数组:\n");
    gets(a);
       printf("输入组中内容:\n");
	gets(b);
while(a[i])
{
 if(a[i]==b[size])
 {
  c++;

 }
 if(a[i]=='\0')
 {
  break;
 }
 i++;

}
printf("%d\n",c);
return 0;
}
