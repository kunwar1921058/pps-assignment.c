## ***Submitted By :***
##### ***Name : Kunwar***           
##### ***Roll No. : 1921058***
##### ***Branch : Information Tecnology(I.T)***
##### ***Section  : I.T. A2***


# My C programes
## 1:To find sum of two numbers
```

     // to find sum of two numbers
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**:
```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
## 2:To print hello world

```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```
**OUTPUT:**
``` 
 Hello world
```
## 3:to print face
```
/ / To print face
#include<stdio.h>
int a();
int b();
int c();
int d();
int main()
{
a();
b();
c();
d();
}
int a()
{
puts(" GURU NANAK DEV ENGINEERING COLLEGE");
}
int b()
{
puts("DEPARTMENT OF INFORMATION TECHNOLOGY")
}
int c()
{
puts("___________________________");
puts("|    xxxxxxxxxxxxxxx      |");
puts("|    (   ^     ^   )      |");
puts("|    (   0     0   )      |");
puts("|     \\     |     /       |");
puts("|      \\    =    /        |");
puts("|       \\_______/         |");
puts("|            |            |");
puts("|____________|____________|");
}
int d()
{
puts("       KUNWAR ARORA");
}
}
```
**OUTPUT:**
```
 GURU NANAK DEV ENGINEERING COLLEGE
DEPARTMENT OF INFORMATION TECHNOLOGY
___________________________
|    xxxxxxxxxxxxxxx      |
|      (   ^     ^   )      |
|      (   0     0   )      |
|       \     |     /       |
|        \    =    /        |
|         \_______/         |
|              |            |
|____________|____________|
       KUNWAR ARORA
```
## 4:To fill your information

```
  / /   To fill your information
#include<stdio.h>

  void info();
  int main()
  {
     info();
  }

   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nYour roll no is %d\nMy phone number is %ld\n My age is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = kunwar

Roll no=1921058

Age = 18

Phone no.= 9988988833

The name is kunwar
Your roll no is 1921058
My phone number is 9988988833
 My age is 18
 ```
## 5:To show area,perimeter,volume of square
```
   
 / / Area,premiter,volume of square
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
```
## 6:To print a table
```
#include<stdio.h>
int main()
{
int a,b,c,d;
printf("enter the starting no. and ending no. ");
scanf("%d %d",&a,&b);
for(c=a;c<=b;c++)
{
for(d=1;d<=10;d++)
{
printf("\n %d x %d=%d",c,d,c*d);
}
}
return 0;
}
```
**OUTPUT:**
```
enter the starting no. and ending no. 8 10

 8 x 1=8
 8 x 2=
 8 x 7=56
 8 x 8=64
 8 x 9=72
 8 x 10=80
 9 x 1=9
 9 x 2=18
 9 x 3=27
 9 x 4=36
 9 x 5=45
 9 x 6=54
 9 x 7=63
 9 x 8=72
 9 x 9=81
 9 x 10=90
 10 x 1=10
 10 x 2=20
 10 x 3=30
 10 x 4=40
 10 x 5=50
 10 x 6=60
 10 x 7=70
 10 x 8=80
 10 x 9=90
 10 x 10=100

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTU4Nzg4MywxNjg4NzMzMDI1LC0xMTU4Mz
k0ODAxLC0xNzk3MjU3MjQ1LC01MTY3Mzk2NDgsLTM2MjI3ODc0
MiwtMTk2NjY4ODA4MywxNDMzODAwOTI4LDcwMzc0OTkyOV19
-->