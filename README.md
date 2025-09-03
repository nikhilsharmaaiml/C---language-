#include <stdio.h>
//CHAPTER-1 VARIABLES,DATATYPES+INPUT/OUTPUT 



int main() 
{
    // Printing variables
    printf("Hello, World! \n");
    int age = 22;
    float pi = 3.14;
    char hashtag = '#';
    printf("Age is %d \n", age);
    printf("Value of pi is %f \n", pi);
    printf("Hashtag looks like this: %c \n", hashtag);

    // Sum of two numbers
    int a, b;
    printf("Enter a: ");
    scanf("%d", &a);
    printf("Enter b: ");
    scanf("%d", &b);
    printf("Sum is: %d\n", a + b);

    // Area of square
    int side;
    printf("Enter side: ");
    scanf("%d", &side);
    printf("Area of square is: %d\n", side * side);

    // Area of circle
    float radius;
    printf("Enter radius: ");
    scanf("%f", &radius);
    printf("Area of circle is: %f\n", 3.14 * radius * radius);

    // Perimeter of rectangle
    int length, width, perimeter;
    printf("Enter length of rectangle: ");
    scanf("%d", &length);
    printf("Enter width of rectangle: ");
    scanf("%d", &width);
    perimeter = 2 * (length + width);
    printf("Perimeter of rectangle = %d\n", perimeter);

    // Cube of a number
    int n;
    printf("Enter n: ");
    scanf("%d", &n);
    printf("Cube is: %d\n", n * n * n);

    return 0;
}