# C-programing
#include <stdio.h>

int main(void) {
	char st1[10];
	char st2[20];
	int i=0;
	printf("Enter the name: \n");
	scanf("%s",st1);
	while(st1[i]!='\0'){
		st2[i]=st1[i];
		++i;
	}
	st2[i]='\0';
	printf("original name: %s\n",st1);
	printf("Trevised name: %s",st2);
	return 0;
}
