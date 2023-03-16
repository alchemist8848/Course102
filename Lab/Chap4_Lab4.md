```c
#include <stdio.h>

int main() {
  char letter;
  float decimal;
  int number;

  printf("Enter a character, a decimal number, and an integer (separated by spaces): ");
  scanf(" %c %f %d", &letter, &decimal, &number);

  printf("Character: %c\n", letter);
  printf("Decimal: %.2f\n", decimal);
  printf("Integer: %d\n", number);

  return 0;
}
