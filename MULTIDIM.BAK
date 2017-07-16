#include<stdio.h>
#include<conio.h>
#include<graphics.h>
#include<math.h>

void main()
{
clrscr();
int i,j,angle,data[8][5]={2,2,4,6,8,
			  3,3,5,7,9,
			  4,4,10,3,4,
			  5,5,5,5,5,
			  3,6,5,4,3,
			  3,8,9,5,2,
			  5,7,3,2,3,
			  3,5,7,7,7};
int gd=0,gm,x,y;
initgraph(&gd,&gm,"");
x=getmaxx();
y=getmaxy();

line(0,0,0,y);
line(0,y,x,y);

	for(i=0;i<8;i++)
	{
		for(j=2,angle=0;j<5;j++)
		{
			setcolor(j+2);
			line(50*data[i][0],y-50*data[i][1],50*data[i][0]+10*data[i][j]*cos((2-j)*240*3.14/360),y-50*data[i][1]+10*data[i][j]*sin((2-j)*240*3.14/360));
		}
	}

getch();
closegraph();
}