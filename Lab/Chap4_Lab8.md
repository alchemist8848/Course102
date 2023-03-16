```c
#include <stdio.h>

int main() {
  char name[100];
  int exam1, exam2, exam3;
  float average;

  printf("Enter student's name: ");
  fgets(name, 100, stdin);

  printf("Enter first exam score: ");
  scanf("%d", &exam1);

  printf("Enter second exam score: ");
  scanf("%d", &exam2);

  printf("Enter third exam score: ");
  scanf("%d", &exam3);

  average = (exam1 + exam2 + exam3) / 3.0;

  printf("\nStudent name: %s", name);
  printf("Exam 1: %d\n", exam1);
  printf("Exam 2: %d\n", exam2);
  printf("Exam 3: %d\n", exam3);
  printf("Average: %.2f\n", average);

  return 0;
}
