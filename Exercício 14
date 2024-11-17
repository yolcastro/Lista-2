#include <stdio.h>

int main() {
    int a, b, c, total = 0;

    printf("Digite os limites da faixa:\n");
    scanf("%d %d", &a, &b);

    if (a > b) {
        int d;
        d = a;
        a = b;
        b = d;
    }
    
    printf("Quantidade de números divisíveis por 3:\n");
    for (c = a; c <= b; c++) {
        if (c % 3 == 0) {
        total++;
        }
    }

    printf("%d", total);

    return 0;
}
