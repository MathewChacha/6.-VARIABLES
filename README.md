# 6.-VARIABLES
#include <stdio.h>
extern int a, b;
extern int c;
int main () {

int a, b, c;
/* actual initialization*/
a=7;
b=14;
/*using addition operator*/
c= a + b;
/*display the result*/
printf("Sum is : %d\n",c);
return 0;
}
