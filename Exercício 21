#include <stdio.h>

int main () {
    int n, n1, n2, n4, n5;

    do {
        printf("Digite um número de cinco dígitos:\n");
        scanf("%d", &n);
    
        if (n > 99999 || n < 10000) {
            printf("Número deve conter cinco dígitos.\n");
        }
    } while (n > 99999 || n < 10000);
    
    n1 = n / 10000;
    n2 = (n / 1000) % 10;
    n4 = (n / 10) % 10;
    n5 = n % 10;

    if (n1 == n5 && n2 == n4) {
        printf("%d é um palíndromo.\n", n);
    }
    else {
        printf("%d NÃO é um palíndromo.\n", n);
    }
    
    return 0;
}
