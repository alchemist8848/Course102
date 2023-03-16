```c
#include <stdio.h>
int main() {
    int number, sum = 0, i = 1;
    printf("Enter a number: ");
    scanf("%d", &number);
    do {
        sum += i;
        i++;
    } while (i <= number);
    printf("Sum of numbers from 1 to %d: %d\n", number, sum);
    return 0;
}
