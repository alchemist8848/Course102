```c
#include <stdio.h>

int main() {
  int var1 = 10; 
  const int var2 = 20; 

  printf("The value of variable var1 is %d\n", var1);
  printf("The value of constant var2 is %d\n", var2);

  var1 = 30; 
  // var2 = 40; // This line will result in an error

  printf("The updated value of variable var1 is %d\n", var1);
  printf("The value of constant var2 is still %d\n", var2);

  return 0;
}
