```c
#include <stdio.h>

int main() {
  int marks;
  char class[10];

  printf("Enter your class and marks (separated by a space): ");
  scanf("%s %d", class, &marks);

  printf("Your class is %s and your marks are %d\n", class, marks);

  return 0;
}
