#include <stdio.h>

int main() {
    // Variáveis da carta 1
    char estado1;
    char codigo1[4];
    char cidade1[50];
    int populacao1;
    float area1;
    float pib1;
    int pontos1;

    // Variáveis da carta 2
    char estado2;
    char codigo2[4];
    char cidade2[50];
    int populacao2;
    float area2;
    float pib2;
    int pontos2;

    // Entrada dos dados da carta 1
    printf("Cadastro da primeira carta:\n");
    printf("Estado (letra): ");
    scanf(" %c", &estado1);
    printf("Código da carta (ex: A01): ");
    scanf("%s", codigo1);
    printf("Nome da cidade: ");
    scanf(" %[^\n]s", cidade1);
    printf("População: ");
    scanf("%d", &populacao1);
    printf("Área (em km2): ");
    scanf("%f", &area1);
    printf("PIB (em bilhões): ");
    scanf("%f", &pib1);
    printf("Número de pontos turísticos: ");
    scanf("%d", &pontos1);

    // Entrada dos dados da carta 2
    printf("\nCadastro da segunda carta:\n");
    printf("Estado (letra): ");
    scanf(" %c", &estado2);
    printf("Código da carta (ex: B02): ");
    scanf("%s", codigo2);
    printf("Nome da cidade: ");
    scanf(" %[^\n]s", cidade2);
    printf("População: ");
    scanf("%d", &populacao2);
    printf("Área (em km2): ");
    scanf("%f", &area2);
    printf("PIB (em bilhões): ");
    scanf("%f", &pib2);
    printf("Número de pontos turísticos: ");
    scanf("%d", &pontos2);

    // Cálculo da densidade populacional e PIB per capita (simplesmente direto no printf)
    float densidade1 = populacao1 / area1;
    float densidade2 = populacao2 / area2;

    float pibPerCapita1 = pib1 / populacao1;
    float pibPerCapita2 = pib2 / populacao2;

    // Exibindo os dados cadastrados
    printf("\n--- CARTA 1 ---\n");
    printf("Cidade: %s\n", cidade1);
    printf("Estado: %c\n", estado1);
    printf("Código: %s\n", codigo1);
    printf("População: %d\n", populacao1);
    printf("Área: %.2f km²\n", area1);
    printf("PIB: %.2f bilhões\n", pib1);
    printf("Pontos turísticos: %d\n", pontos1);
    printf("Densidade populacional: %.2f hab/km²\n", densidade1);
    printf("PIB per capita: %.6f bilhões/hab\n", pibPerCapita1);

    printf("\n--- CARTA 2 ---\n");
    printf("Cidade: %s\n", cidade2);
    printf("Estado: %c\n", estado2);
    printf("Código: %s\n", codigo2);
    printf("População: %d\n", populacao2);
    printf("Área: %.2f km²\n", area2);
    printf("PIB: %.2f bilhões\n", pib2);
    printf("Pontos turísticos: %d\n", pontos2);
    printf("Densidade populacional: %.2f hab/km²\n", densidade2);
    printf("PIB per capita: %.6f bilhões/hab\n", pibPerCapita2);

    // Comparação por população (atributo fixo)
    printf("\n--- COMPARAÇÃO: POPULAÇÃO ---\n");

    if (populacao1 > populacao2) {
        printf("Vencedora: Carta 1 (%s), com maior população: %d habitantes\n", cidade1, populacao1);
    } else if (populacao2 > populacao1) {
        printf("Vencedora: Carta 2 (%s), com maior população: %d habitantes\n", cidade2, populacao2);
    } else {
        printf("Empate: As duas cidades têm a mesma população.\n");
    }

    return 0;
}
