#include <stdio.h>

void conversor (int n) {    
    for (int i = 15; i >= 0; i--) {
        printf("%d", (n >> i) & 1);
        if (i % 4 == 0) {
            printf(" ");
        }
    }
}

int main() {
    for (int n = 1; n <= 256; n++) {
        printf("Decimal: %d\n", n);

        printf("Binário: ");
        conversor(n);
        printf("\n");

        printf("Octal: %o\n", n);

        printf("Hexadecimal: %X\n", n);

        printf("\n");
    }

    return 0;
}
