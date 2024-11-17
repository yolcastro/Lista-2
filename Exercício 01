#include <stdio.h>

void dia (int num) {
    switch (num) {
        case 1: printf("Domingo.\n");
        break;
        case 2: printf("Segunda-feira.\n");
        break;
        case 3: printf("Terça-feira.\n");
        break;
        case 4: printf("Quarta-feira.\n");
        break;
        case 5: printf("Quinta-feira.\n");
        break;
        case 6: printf("Sexta-feira.\n");
        break;
        case 7: printf("Sábado.\n");
        break;
        default: printf("Número de dia não válido\n.");
    }
}

int main() {
    int num;
    
    printf("Digite um número de 1 a 7 para o dia da semana ou 0 para sair: \n");
    scanf("%d", &num);
    
    while (num != 0) {
        dia(num);
        printf("Digite um número de 1 a 7 para o dia da semana ou 0 para sair: \n");
        scanf("%d", &num);
    }

    return 0;
}
