```c
#include <stdio.h>
int main()
{
    int grade;
    printf("Enter your grade: ");
    scanf("%d", &grade);
    if (grade >= 90)
        printf("You got an A");
    else if (grade >= 80)
        printf("You got a B");
    else if (grade >= 70)
        printf("You got a C");
    else if (grade >= 60)
        printf("You got a D");
    else
        printf("You got an F");
    return 0;
}
