#include <stdio.h>

int main() {
    int idade;

    printf("Digite a idade do nadador: ");
    scanf("%d", &idade);

    if (idade >= 5 && idade <= 7) {
        printf("Nadador de idade %d é da categoria Infantil A.\n", idade);
    }
    else if (idade >= 8 && idade <= 10) {
        printf("Nadador de idade %d é da categoria Infantil B.\n", idade);
    }
    else if (idade >= 11 && idade <= 13) {
        printf("Nadador de idade %d é da categoria Juvenil A.\n", idade);
    }
    else if (idade >= 14 && idade <= 17) {
        printf("Nadador de idade %d é da categoria Juvenil B.\n", idade);
    }
    else if (idade > 17) {
        printf("Nadador de idade %d é da categoria Sênior.\n", idade);
    }
    else {
        printf("Idade inválida para classificação.\n");
    }

    return 0;
}