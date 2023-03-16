```c
#include <stdio.h>

int main() {
   int i = 1, j = 1;
   char c = 'A';

   while (i <= 5) {
      while (j <= i) {
         printf("%c ", c);
         c++;
         j++;
      }
      printf("\n");
      i++;
      j = 1;
   }
   return 0;
}
