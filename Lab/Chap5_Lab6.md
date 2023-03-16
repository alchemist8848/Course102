```c
#include <stdio.h>

int main ()
{
  int items;
  float cost;

  printf ("Enter the number of items: ");
  scanf ("%d", &items);

  switch (items)
    {
    case 1:
      cost = 5.0;
      break;
    case 2:
      cost = 8.5;
      break;
    case 3:
      cost = 11.0;
      break;
    case 4:
      cost = 15.0;
      break;
    default:
      cost = 1000.0;
    }

  printf ("The cost of the meal is $%.2f\n", cost);
  return 0;
}
