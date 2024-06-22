# lecuture---09---cipher-schools-


In this lecture i learned what are the loops and what are they how to use them
and what are the uses of them and how to declare and intilalize them and 
leaned syntax of a single loop and how to print a single a loop 
#include <iostream>

int main() {
    const int SIZE = 5;  // Define the number of inputs
    int numbers[SIZE];   // Declare an array of integers

    // Prompt the user for input and store in the array
    std::cout << "Enter 5 numbers:" << std::endl;
    for (int i = 0; i < SIZE; ++i) {
        std::cout << "Enter number " << (i + 1) << ": ";
        std::cin >> numbers[i];
    }

    // Print the numbers in reverse order using a single loop
    std::cout << "The numbers in reverse order are:" << std::endl;
    for (int i = SIZE - 1; i >= 0; --i) {
        std::cout << numbers[i] << " ";
    }
    std::cout << std::endl;

    return 0;
}
