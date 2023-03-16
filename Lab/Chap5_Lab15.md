```c
#include <stdio.h>
int main() {
    int number, i, factorial = 1;
    printf("Enter a number: ");
    scanf("%d", &number);
    i = number;
    do {
        factorial *= i;
        i--;
    } while (i >= 1);
    printf("Factorial of %d: %d\n", number, factorial);
    return 0;
}
