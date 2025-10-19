# Par_e_Impar_emC
Código básico para saber se um número é par ou ímpar em C. 
#include <stdio.h>

int main () {
    int numero; 
    printf("Digite um número:\n");
    scanf("%d", &numero);

     if (numero % 2 == 0) {
    printf("O número %d é PAR.\n", numero);

    } else {

        printf("O número %d é ÍMPAR.\n", numero);
    }    

    return 0;

    }
