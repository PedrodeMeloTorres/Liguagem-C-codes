# Liguagem-C-codes
Desafio Aula dia 29/05

## Questão 34

#include <stdio.h>

int main(void){
    int nome, idade, endereco, numero;
    printf("Digite seu nome, idade, endereco e numero: ");
    scanf("%d" , &nome);
    scanf("%d" , &idade);
    scanf("%d" , &endereco);
    scanf("%d", &numero);
    printf("Seu nome é %d você tem %d anos mora na rua %d e seu telefone é %d", nome, idade, endereco, numero);
    return 0;
}
