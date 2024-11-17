#include <stdio.h>

int main() {
    int a, b, c, somatorio = 0;

    printf("Digite os limites da faixa:\n");
    scanf("%d %d", &a, &b);

    if (a > b) {
        int d;
        d = a;
        a = b;
        b = d;
    }
    
    for (c = a; c <= b; c++) {
        if (c % 2 == 0) {
        somatorio = somatorio + c;
        }
    }

    printf("%d\n", somatorio);

    return 0;
}
