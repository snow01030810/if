# 分支与循环——if语句
#include <stdio.h>
int main()
{
	int a = 0;
	scanf_s("%d", &a);
	if (a < 5)
	printf("<5");
	else if (a == 5)
	printf("= 5");
	if (a > 5)
	printf(">5");
	
	return 0;
}
