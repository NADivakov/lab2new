#include <stdio.h>
#include <stdlib.h>

enum Month
{
	January = 1,
	February,
	March,
	April,
	May,
	June,
	July,
	August,
	September,
	October,
	November,
	December
};

int main(int argc, char *argv[]) {
	char* Month[] = {"January","February","March","April","May","June", 
	"July","August","September","October","November","December"};
	
	enum Month month;
	printf("Enter number of month: ");
	for(;;){
	scanf("%d", &month);
	switch(month){
		case January: printf("Month: %s\n", Month[0]); break;
		case February: printf("Month: %s\n", Month[1]); break;
		case March: printf("Month: %s\n", Month[2]); break;
		case April: printf("Month: %s\n", Month[3]); break;
		case May: printf("Month: %s\n", Month[4]); break;
		case June: printf("Month: %s\n", Month[5]); break;
		case July: printf("Month: %s\n", Month[6]); break;
		case August: printf("Month: %s\n", Month[7]); break;
		case September: printf("Month: %s\n", Month[8]); break;
		case October: printf("Month: %s\n", Month[9]); break;
		case November: printf("Month: %s\n", Month[10]); break;
		case December: printf("Month: %s\n", Month[11]); break;
		default: printf("Maybe you entered something incorrect. Try again!\n");
	}
}
	return 0;
}
