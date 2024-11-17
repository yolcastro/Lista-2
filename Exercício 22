#include <stdio.h>
#include <math.h>

int main () {
    int n, verdadeiro = 0;

    printf("Digite um número:\n");
    scanf("%d", &n);

    if (n < 0) {
        n = -n;
    }

    do {
        if (n % 10 == 7) {
            verdadeiro = 1;
            break;
        }

        n = n / 10;
    } while (n > 0);
    
    if (verdadeiro == 1) {
        printf("O algarismo 7 está presente no número.\n");
    }
    else {
        printf("O algarismo 7 NÃO está presente no número.\n");
    }

    return 0;
}
