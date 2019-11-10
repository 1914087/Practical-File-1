# PPS Assignment
## Sarvanshdeep Singh Sahota,Civil B2, 1914100
**1. TO Store the of marks scored by students**
     #include<stdio.h>
int main()
{
   int i,n,marks;
   char name[30];
   printf("Enter the number of students:");
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
      printf("Enter the name:",name);
      scanf("%s",name);
      printf("Enter marks:",marks);
      scanf("%d",&marks);
   }
   return 0;
}
_Output:-_
Enter the number of students:4
Enter the name:Sarvansh
Enter the marks:6
Enter the name:Sahil
Enter the marks:7
Enter the name:Ritik
Enter the marks:8
Enter the name:Manthan
Enter the marks:9
