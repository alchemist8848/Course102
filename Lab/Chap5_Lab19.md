```c
#include <stdio.h>

int main() {
    int i;

    printf("Demonstrating the break statement:\n");
    for (i = 0; i < 10; i++) {
        if (i == 5) {
            break;
        }
        printf("%d ", i);
    }
    printf("\n");

    printf("Demonstrating the continue statement:\n");
    for (i = 0; i < 10; i++) {
        if (i % 2 == 0) {
            continue;
        }
        printf("%d ", i);
    }
    printf("\n");

    printf("Demonstrating the goto statement:\n");
    for (i = 0; i < 10; i++) {
        if (i == 5) {
            goto jump;
        }
        printf("%d ", i);
    }
    jump:
    printf("Jumped!\n");

    return 0;
}
