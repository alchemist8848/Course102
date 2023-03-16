```c
#include <stdio.h>

int main() {
    float price = 20.0; // Declare and initialize a variable to store the price of a product
    const float tax = 0.08; // Declare and initialize a constant to store the tax rate

    float total_price = price + (price * tax); // Calculate the total price including tax

    printf("The price of the product is $%.2f\n", price);
    printf("The tax rate is %.2f%%\n", tax * 100);
    printf("The total price of the product including tax is $%.2f\n", total_price);

    // Update the price of the product
    price = 25.0;
    total_price = price + (price * tax); // Recalculate the total price including tax

    printf("\nThe updated price of the product is $%.2f\n", price);
    printf("The total price of the product including tax is now $%.2f\n", total_price);

    return 0;
}
