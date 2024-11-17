#include <stdio.h>

int main() {
    int voto, digito;
    int paulo = 0, renata = 0, nulo = 0, branco = 0;

    while (1) {
        printf("Insira o seu voto:\n");
        scanf("%d", &voto);

        if (voto < 0) {
            break;
        }

        printf("Seu voto é %d. Aperte 0 para cancelar e 1 para confirmar:\n", voto);
        scanf("%d", &digito);

        if (digito == 0) {
            continue; 
        }

        if (voto == 5) {
            paulo++;
        } else if (voto == 7) {
            renata++;
        } else if (voto == 0) {
            nulo++;
        } else {
            branco++;
        }
    }

    printf("Quantidade de votos:\n");
    printf("Paulo: %d\n", paulo);
    printf("Renata: %d\n", renata);
    printf("Nulo: %d\n", nulo);
    printf("Branco: %d\n", branco);

    return 0;
}
