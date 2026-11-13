# radhika
#include <stdio.h>

int main() {
    int firstNumber, secondNumber, sum;
    
    // Ask the user for input
    printf("Enter two integers: ");
    scanf("%d %d", &firstNumber, &secondNumber);

    // Calculate the sum
    sum = firstNumber + secondNumber;      
    
    // Display the result
    printf("%d + %d = %d\n", firstNumber, secondNumber, sum);
    
    return 0;
}
