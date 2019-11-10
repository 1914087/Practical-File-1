#          **PROGRAMMING FOR PROGRAM SOLVING ESC-18105** 
##         **Sarvanshdeep Singh Sahota**
##         **Civil B2** 
##         **1914100**
#          **GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA**
##         **Department of Civil Engineering**
![LOGO](https://raw.githubusercontent.com/01eyon/1914100/master/logo.jpg)
**1. To Store the of marks scored by students**
       
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
**2. Program to add 2 numbers:-**

    #include<stdio.h>
    int main()
    {
       int a,b,c;
       printf("Enter the value of a:");
       scanf("%d",&a);
       printf("Enter the value of b:");
       scanf("%d",&b);
       printf("The sum of a and b is %d",c=a+b);
       return 0;
    }

    _Output:-_
     Enter the value of a:33
     Enter the value of b:56
     The sum of a and b is 89
**3. Program to print any table:-**

    #include<stdio.h>
    int main()
    {
       int x, y, z;
       printf("Enter the table you want to print:");
       scanf("%d",&x);
       for(y=1;y<=10;y++)
         {
           printf("\n%d x %d =%d\n",x,y,z=x*y);
         }
       return 0;
    }

    _Output:-_
     Enter the table you want to print:89
     89 x 1=89
     89 x 2=178
     89 x 3=267
     89 x 4=356
     89 x 5=445
     89 x 6=534
     89 x 7=623
     89 x 8=712
     89 x 9=801
     89 x 10=890
**4. Program to print hello world**

    #include<stdio.h>
    int main()
    {
       puts("_____________");
       puts("|Hello World"|);
       puts("_____________");
    }

    _Output:-_
    _____________
    |Hello World|
    _____________
**5. To print PPS Using puts:-**

    #include<stdio.h>
    int main()
    {
       puts("zzzzzzzzzzz");
       puts("          z");
       puts("         z ");
       puts("        z  ");
       puts("       z   ");
       puts("      z    ");
       puts("     z     ");
       puts("    z      ");
       puts("   z       ");
       puts("  z        ");
       puts(" z         ");
       puts("zzzzzzzzzzz");
    }

    _Output:-_
    zzzzzzzzzzz
             z
            z
           z
          z
         z
        z
       z
      z
     z
    zzzzzzzzzzz
