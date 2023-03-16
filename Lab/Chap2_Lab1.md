```c
#include <stdio.h>

int main() {
  int x = 10;
  float y = 3.14;
  char z = 'A';

  printf("The initial value of x is %d\n", x);
  printf("The initial value of y is %.2f\n", y);
  printf("The initial value of z is %c\n", z);

  x = 20;
  y = 6.28;
  z = 'B';

  printf("The modified value of x is %d\n", x);
  printf("The modified value of y is %.2f\n", y);
  printf("The modified value of z is %c\n", z);

  return 0;
}
