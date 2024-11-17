#include <stdio.h>

int main() {
    unsigned char x, y;

    printf("Digite valores para X e Y:\n");
    scanf("%hhu %hhu", &x, &y);

    if (y < 5) {
        printf("O valor de Y não pode ser menor do que 5.");
        return 0;
    }

    unsigned char limpar_anteriores, limpar_posteriores;

    limpar_anteriores = 0xF0;
    limpar_posteriores = 0x0F;    

    y = y & limpar_anteriores;
    y = y | (x & limpar_posteriores);

    printf("Resultado: %hhu\n", y);

    return 0;
}
