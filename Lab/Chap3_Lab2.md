```c
#include <stdio.h>

int main() {
    int a = 10, b;

    printf("a before increment: %d\n", a);
    b = ++a;
    printf("prefix increment: %d\n", b);
    b = a++;
    printf("postfix increment: %d\n", b);
    printf("a after increment: %d\n", a);

    printf("a before decrement: %d\n", a);
    b = --a;
    printf("prefix decrement: %d\n", b);
    b = a--;
    printf("postfix decrement: %d\n", b);
    printf("a after decrement: %d\n", a);

    return 0;
}
