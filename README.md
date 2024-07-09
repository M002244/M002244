#include <stdio.h>

int main() {
    float length1, width1, area1;
    float length2, width2, area2;

    // Input for Rectangle 1
    printf("Enter length and width of Rectangle 1: ");
    scanf("%f %f", &length1, &width1);

    // Calculate area of Rectangle 1
    area1 = length1 * width1;

    // Input for Rectangle 2
    printf("Enter length and width of Rectangle 2: ");
    scanf("%f %f", &length2, &width2);

    // Calculate area of Rectangle 2
    area2 = length2 * width2;

    // Print areas of both rectangles
    printf("Area of Rectangle 1 = %.2f\n", area1);
    printf("Area of Rectangle 2 = %.2f\n", area2);

    // Determine and print which rectangle has the maximum area
    if (area1 > area2) {
        printf("Rectangle 1 has the larger area.\n");
    } else if (area2 > area1) {
        printf("Rectangle 2 has the larger area.\n");
    } else {
        printf("Both rectangles have the same area.\n");
    }

    return 0;
}

