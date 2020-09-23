<div align="center">

## sum of even,odd numbers


</div>

### Description

This code is useful to compute the sum of odd , even numbers and both upto certain limit.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[lakshmi\.G](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lakshmi-g.md)
**Level**          |Beginner
**User Rating**    |3.0 (6 globes from 2 users)
**Compatibility**  |C
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lakshmi-g-sum-of-even-odd-numbers__3-13403/archive/master.zip)





### Source Code

```
#include<stdio.h>
#include<conio.h>
void main()
{
int n,se=0,so=0,ch,i;
clrscr();
printf("enter the number limit:");
scanf("%d",&n);
printf("\n1.odd\n2.even\n3.both\n");
printf("enter your choice of displaying the result:");
scanf("%d",&ch);
for(i=0;i<=n;i++)
{
if(i%2==0)
se=se+i;
}
for(i=0;i<=n;i++)
{
if(i%2!=0)
so=so+i;
}
switch(ch)
{
case 1:
printf("\nsum of even numbers=%d",se);
break;
case 2:
printf("\nsum of odd numbers=%d",so);
break;
case 3:
printf("\nsum of even numbers=%d",se);
printf("\nsum of odd numbers=%d",so);
printf("\nsum of both numbers=%d",(so+se));
break;
default:
printf("\nenter a valid choice\n");
}
getch();
}
```

