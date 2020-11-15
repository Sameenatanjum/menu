# menu
program to choose the food using random choices(1-5)
#include<stdio.h>
main()
{
	int x=0;
	printf("MENU\n");
	printf("Choose a dish of your choice:\n");
    scanf("%d",&x);
	switch(x)
	{
		case 1:printf("1.Nuggets \nrs.200");
		break;
		case 2:printf("2.Noodles \nrs.210");
		break;
		case 3:printf("3.Pasta \nrs.179");
		break;
		case 4:printf("4.Burger \nrs.149");
		break;
		case 5:printf("5.French fries \nrs.99 ");
		break;
	}
}
