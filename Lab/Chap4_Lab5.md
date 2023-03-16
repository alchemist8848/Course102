```c
#include <stdio.h>

int main() {
  int number;
  float decimal;
  char letter;
  char word[100];

  printf("Enter an integer: ");
  scanf("%d", &number);

  printf("Enter a decimal number: ");
  scanf("%f", &decimal);

  printf("Enter a character: ");
  scanf(" %c", &letter);

  printf("Enter a word: ");
  scanf("%s", word);

  printf("\nYou entered:\n");
  printf("Integer: %d\n", number);
  printf("Decimal: %.2f\n", decimal);
  printf("Character: %c\n", letter);
  printf("Word: %s\n", word);

  return 0;
}
