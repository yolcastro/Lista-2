#include <stdio.h>
#include <math.h>

int main() {
    int i, termos;
    float leibniz, somatorio = 0, pi;

    printf("Insira quantos termos da Série de Leibniz você deseja para aproximar o valor de Pi:\n");
    scanf("%d", &termos);

    for (i = 0; i < termos; i++) {
        leibniz = pow(-1, i) / (2 * i + 1);
        somatorio = somatorio + leibniz;
        pi =  4 * somatorio;

        printf("Valor de Pi aproximado com %d termos: %f\n", i + 1, pi);
    }
    
    return 0;
}
