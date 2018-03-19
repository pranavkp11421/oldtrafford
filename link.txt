#include<stdio.h>
struct node
{
int data;
struct node *link;
}a[10];
main()
{
int ch,z=1,
while(z)
{
printf("STACK USING LINKED LIST\n");
printf("1.PUSH\n2.POP\n3.DISPLAY\n4.EXIT\n");
printf("enter your choice:");
scanf("%d",&ch);
switch(ch)
{
case 1:printf("\n")
