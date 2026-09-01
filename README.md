#include <stdio.h>

int main() {
    int op;

    printf("Digite o numero do mes (1 a 12): ");
    scanf("%d", &op);

    switch (op) {
        case 1:
            printf("Janeiro tem 31 dias.\n");
            break;

        case 2:
            printf("Fevereiro tem 28 dias.\n");
            break;

        case 3:
            printf("Marco tem 31 dias.\n");
            break;

        case 4:
            printf("Abril tem 30 dias.\n");
            break;

        case 5:
            printf("Maio tem 31 dias.\n");
            break;

        case 6:
            printf("Junho tem 30 dias.\n");
            break;

        case 7:
            printf("Julho tem 31 dias.\n");
            break;

        case 8:
            printf("Agosto tem 31 dias.\n");
            break;

        case 9:
            printf("Setembro tem 30 dias.\n");
            break;

        case 10:
            printf("Outubro tem 31 dias.\n");
            break;

        case 11:
            printf("Novembro tem 30 dias.\n");
            break;

        case 12:
            printf("Dezembro tem 31 dias.\n");
            break;

        default:
            printf("Mes invalido.\n");
    }

    return 0;
}