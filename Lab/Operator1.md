```c
#include <stdio.h>

int main() {
    int a = 10;
    int b = 5;
    int c;

    // assignment operator
    c = a;
    printf("Value of c = %d\n", c);

    // arithmetic operators
    c = a + b;
    printf("Value of c = %d\n", c);

    c = a - b;
    printf("Value of c = %d\n", c);

    c = a * b;
    printf("Value of c = %d\n", c);

    c = a / b;
    printf("Value of c = %d\n", c);

    c = a % b;
    printf("Value of c = %d\n", c);

    return 0;
}
