# C-
shutdown



#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int main() {
	system("shutdown -s -t 600");
	printf("computer will be shudwdown\n");
	char c[20]={0};
	again:
		printf("说\n");
	scanf("%s", &c);
		printf("%s\n",c);
		if (0 == strcmp("猪", c))
			system("shutdown -a");
		else
			goto again;
	return 0;
}
