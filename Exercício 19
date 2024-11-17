#include <stdio.h>

int main() {
    int a, b, c, d, somatorio = 0, quantidade = 0;
    float media;

    printf("Digite os limites da faixa:\n");
    scanf("%d %d", &a, &b);

    if (a > b) {
    d = a;
    a = b;
    b = d;
    }

    for (c = a; c <= b; c++) {
        somatorio = somatorio + c;
        quantidade++;
    }

    media = (float) somatorio / quantidade;

    printf("Média aritmética: %.2f\n", media);

    return 0;   
}
