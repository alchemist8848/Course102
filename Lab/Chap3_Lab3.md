```c
#include <stdio.h>

int main() {
    int a = 10;

    printf("a before assignment: %d\n", a);
    a += 5;
    printf("a after addition assignment: %d\n", a);
    a -= 2;
    printf("a after subtraction assignment: %d\n", a);
    a *= 3;
    printf("a after multiplication assignment: %d\n", a);
    a /= 4;
    printf("a after division assignment: %d\n", a);
    a %= 5;
    printf("a after modulus assignment: %d\n", a);

    return 0;
}
