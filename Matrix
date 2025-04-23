#include <stdio.h>
#include <stdlib.h>

int main() {
    int a[3][3], b[3][3],c;
    int i, j, k;


    printf("First matrix:\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
            scanf("%d", &a[i][j]);
        }
    }


    printf("Second matrix:\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
            scanf("%d", &b[i][j]);
        }
    }


    printf("Addition :\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
           c = a[i][j] + b[i][j];
            printf("%d ", c);
        }
        printf("\n");
    }


    printf("Subtraction :\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
            c= a[i][j] - b[i][j];
            printf("%d ", c);
        }
        printf("\n");
    }


    printf("Multiplication:\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
            c = 0;
            for (k = 0; k < 3; k++) {
                c += a[i][k] * b[k][j];
            }
            printf("%d ", c);
        }
        printf("\n");
    }


    printf(" Division :\n");
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++) {
            if (b[i][j] != 0) {
                printf("%.2f ", (float)a[i][j] / b[i][j]);
            } else {
                printf("X");
            }
        }
        printf("\n");
    }

    return 0;
}
