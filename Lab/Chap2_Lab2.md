```c
#include <stdio.h>

#define PI 3.14159265

int main() {
  int radius = 5;
  float area;

  area = PI * radius * radius;

  printf("Area of circle with radius %d is %.2f\n", radius, area);

  return 0;
}
