#include<stdio.h>
#include<conio.h>
Void main()
{
int a;
clrscr();
printf("Enter the value of a i.e marks obtained");
scand("%d",&a);
if(a>=40&a<=100)
{
if(a>=85&a<=100)
{
printf("Student has got grade A");
}
if(a>=70&a<=84)
{
printf("Student has got grade B");
}
if(a>=55&a<=69)
{
printf("Student has got grade C");
}
if(a>=40&a<=54)
{
printf("Student has got grade D");
}
}
else
{
Printf ("student has got grade F");
}
getch();
}
