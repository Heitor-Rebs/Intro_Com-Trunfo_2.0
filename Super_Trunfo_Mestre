#include <stdio.h>
#include <string.h>

int main() {
    /* Declarando variáveis */
    char nome[50] = "Brasil",nome2[50] = "Alemanha";
    char atributo[50], atributo2[50];
    int pturistico, pturistico2, opcao, opcao2;
    unsigned long int populacao, populacao2;
    float area, pib, area2, pib2, densidade, densidade2, soma, soma2;

    /* Cadastrando cartas de exemplo */
    /* Carta 1 */
    populacao = 212583750;
    area = 8510417.771;
    pib = 2174;
    pturistico = 8674;

    /* Carta 2 */
    populacao2 = 83166711;
    area2 = 357051;
    pib2 = 4526;
    pturistico2 = 2543;

    /* Calculando Densidade Populacional */
    /* Carta 1 */
    densidade = populacao / area;

    /* Carta 2 */
    densidade2 = populacao2 / area2;

    /* Construindo menu */
    printf("Escolha o primeiro atributo para comparação\n\n");
    printf("(1) População\n");
    printf("(2) Área\n");
    printf("(3) PIB\n");
    printf("(4) Número de pontos turísticos\n");
    printf("(5) Densidade Demográfica\n");
    scanf("%d",&opcao);
    
    /* Utilizando switch para executar a opção escolhida pelo usuário */
    switch (opcao){
        case 1:
            soma = populacao;
            soma2 = populacao2;
            strcpy(atributo, "População");
            
            /* Primeira comparação */
            printf("\nComparação de cartas (Atributo: População)\n");
            printf("Carta 1 - %s - %d\n", nome, populacao);
            printf("Carta 2 - %s - %d\n", nome2, populacao2);
            if (populacao > populacao2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (populacao < populacao2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            
            /* Apresentando o segundo menu, sem a opção já selecionada */
            printf("\n\nEscolha o segundo atributo para comparação\n\n");
            printf("(2) Área\n");
            printf("(3) PIB\n");
            printf("(4) Número de pontos turísticos\n");
            printf("(5) Densidade Demográfica\n");
            scanf("%d",&opcao2);
            break;


        case 2:
            soma = area;
            soma2 = area2;
            strcpy(atributo , "Área");

            printf("\nComparação de cartas (Atributo: Área)\n");
            printf("Carta 1 - %s - %.2f km²\n", nome, area);
            printf("Carta 2 - %s - %.2f km² \n", nome2, area2);
            if (area > area2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (area < area2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }

            printf("\n\nEscolha o segundo atributo para comparação\n\n");
            printf("(1) População\n");
            printf("(3) PIB\n");
            printf("(4) Número de pontos turísticos\n");
            printf("(5) Densidade Demográfica\n");
            scanf("%d",&opcao2);
            break;

        case 3:
            soma = pib;
            soma2 = pib2;
            strcpy(atributo , "PIB");

            printf("\nComparação de cartas (Atributo: PIB)\n");
            printf("Carta 1 - %s - %.2f bilhões de reais \n", nome, pib);
            printf("Carta 2 - %s - %.2f bilhões de reais \n", nome2, pib2);
            if (pib > pib2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (pib < pib2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }

            printf("\n\nEscolha o segundo atributo para comparação\n\n");
            printf("(1) População\n");
            printf("(2) Área\n");
            printf("(4) Número de pontos turísticos\n");
            printf("(5) Densidade Demográfica\n");
            scanf("%d",&opcao2);
            break;

        case 4:
            soma = pturistico;
            soma2 = pturistico2;
            strcpy(atributo , "Nº de Pontos Turísticos");

            printf("\nComparação de cartas (Atributo: Nº de Pontos Turísticos)\n");
            printf("Carta 1 - %s - %d\n", nome, pturistico);
            printf("Carta 2 - %s - %d\n", nome2, pturistico2);
            if (pturistico > pturistico2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (pturistico < pturistico2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }

            printf("\n\nEscolha o segundo atributo para comparação\n\n");
            printf("(1) População\n");
            printf("(2) Área\n");
            printf("(3) PIB\n");
            printf("(5) Densidade Demográfica\n");
            scanf("%d",&opcao2);
            break;

        case 5:
            soma = densidade;
            soma2 = densidade2;
            strcpy(atributo , "Densidade Demográfica");

            printf("\nComparação de cartas (Atributo: Densidade Demográfica)\n");
            printf("Carta 1 - %s - %.2f \n", nome, densidade);
            printf("Carta 2 - %s - %.2f \n", nome2, densidade2);
            if (densidade < densidade2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (densidade > densidade2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }

            printf("\n\nEscolha o segundo atributo para comparação\n\n");
            printf("(1) População\n");
            printf("(2) Área\n");
            printf("(3) PIB\n");
            printf("(4) Número de pontos turísticos\n");
            scanf("%d",&opcao2);
            break;

        default:
            printf("Opção inválida");
    }
    
    switch (opcao2){
        case 1:
            /* Fazendo a soma dos dois atributos */
            soma = soma + populacao;
            soma2 = soma2 + populacao2;
            strcpy(atributo2 , "População");

            printf("\nComparação de cartas (Atributo: População)\n");
            printf("Carta 1 - %s - %d\n", nome, populacao);
            printf("Carta 2 - %s - %d\n", nome2, populacao2);
            if (populacao > populacao2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (populacao < populacao2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            break;

        case 2:
            soma = soma + area;
            soma2 = soma2 + area2;
            strcpy(atributo2 , "Área");

            printf("\nComparação de cartas (Atributo: Área)\n");
            printf("Carta 1 - %s - %.2f km²\n", nome, area);
            printf("Carta 2 - %s - %.2f km² \n", nome2, area2);
            if (area > area2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (area < area2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            break;

        case 3:
            soma = soma + pib;
            soma2 = soma2 + pib2;
            strcpy(atributo2 , "PIB");

            printf("\nComparação de cartas (Atributo: PIB)\n");
            printf("Carta 1 - %s - %.2f bilhões de reais \n", nome, pib);
            printf("Carta 2 - %s - %.2f bilhões de reais \n", nome2, pib2);
            if (pib > pib2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (pib < pib2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            break;

        case 4:
            soma = soma + pturistico;
            soma2 = soma2 + pturistico2;
            strcpy(atributo2 , "Nº de Pontos Turísticos");

            printf("\nComparação de cartas (Atributo: Nº de Pontos Turísticos)\n");
            printf("Carta 1 - %s - %d\n", nome, pturistico);
            printf("Carta 2 - %s - %d\n", nome2, pturistico2);
            if (pturistico > pturistico2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (pturistico < pturistico2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            break;

        case 5:
            soma = soma + densidade;
            soma2 = soma2 + densidade2;
            strcpy(atributo2 , "Densidade Demográfica");

            printf("\nComparação de cartas (Atributo: Densidade Demográfica)\n");
            printf("Carta 1 - %s - %.2f \n", nome, densidade);
            printf("Carta 2 - %s - %.2f \n", nome2, densidade2);
            if (densidade < densidade2){
                printf("Carta 1 (%s) venceu",nome);
            } else if (densidade > densidade2){
                printf("Carta 2 (%s) venceu",nome2);
            } else {
                printf("As cartas empataram");
            }
            break;
    }
    
    /* Fazendo a comparação entre as somas dos dois atributos de cada carta */
    printf("\n\nComparação da soma dos atributos das cartas (Atributos: %s e %s)\n",atributo,atributo2);
    printf("Carta 1 - %s - %.2f \n", nome, soma);
    printf("Carta 2 - %s - %.2f \n", nome2, soma2);
    if (soma > soma2){
        printf("Carta 1 (%s) venceu",nome);
    } else if (soma < soma2){
        printf("Carta 2 (%s) venceu",nome2);
    } else {
        printf("As cartas empataram");
    }

    return 0;
}
