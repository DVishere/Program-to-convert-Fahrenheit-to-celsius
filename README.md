# Program-to-convert-Fahrenheit-to-celsius


#include<stdio.h> 

int main() 
{
    float fahrenheit, celsius;

    printf("Enter the temp in fahrenheit: ");
    scanf("%f", &fahrenheit);

    celsius = (5.0/9) * (fahrenheit - 32);

    printf("%f°F is same as %f°C", fahrenheit, celsius);

    return 0;
} 
