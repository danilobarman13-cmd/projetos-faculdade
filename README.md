#include <stdio.h>

// Desafio Super Trunfo - Países
// Tema 1 - Cadastro das cartas
// Objetivo: No nível novato você deve criar as cartas representando as cidades utilizando scanf para entrada de dados e printf para exibir as informações.
// inserçao de dados para o jogo

int main() {
  // Área para definição das variáveis para armazenar as propriedades das cidades
int main(){

  // Área para entrada de dados
// decalarações das variaveis da carta 1

  // Área para exibição dos dados da cidade
   char estado1[50], codigo1[10], cidade1[50];
   unsigned long int população1;
   int pontosturisticos1;
   float area1, pib1;

return 0;
} 
// dados da primeira cidade

   printf("digite o nome do estado:\n");
   scanf("%s", estado1);
   printf("digite a cidade:\n");
   scanf("%s", cidade1);
   printf("digite o codigo:\n");
   scanf("%s", codigo1);
   printf("digite a população:\n");
   scanf("%lu", &população1);
   printf("digite a area:\n");
   scanf("%f", &area1);
   printf("digite o pib:\n");
   scanf("%f", &pib1);
   printf("digite o numero de pontos turisticos:\n");
   scanf("%d", &pontosturisticos1);

   // declaração das variaveis adcionais da cidade 1

   float pibpercapita1 = pib1 / população1;
   float densidadepop1 = população1 / area1;

   // declaração da densidade invertida

   float densidadeinv1 = 1.0 / densidadepop1;

   float superpoder1 = população1 + area1 + pib1 + pibpercapita1 + pontosturisticos1 + densidadeinv1;


// informaçoes dos dados da primeira carta

   printf("\n---informacões da primeira carta---\n");

   printf("o estado é: %s\n a cidade é: %s\n o codigo é: %s\n", estado1, cidade1, codigo1);
   printf("a população é: %lu\n", população1);
   printf("a área é: %f\n o pib é: %f\n", area1, pib1);
   printf("o numero de pontos turisticos é: %d\n", pontosturisticos1);
   printf("o pib percapita é: %f\n a densidade é: %f\n", pibpercapita1, densidadepop1);
   printf(" o super poder é: %f\n", superpoder1);


// variaveis cidade 2

   char cidade2 [50], codigo2 [5], estado2[50];
   unsigned long int população2;
   int pontosturisticos2;
   float pib2, área2;

   // inserção de dados da segunda carta

   printf("digite do estado: \n");
   scanf("%s", estado2);
   printf("digite a cidade: \n");
   scanf("%s", cidade2);
   printf("digite o codigo: \n");
   scanf("%s", codigo2);
   printf("digite a população: \n");
   scanf("%lu", &população2);
   printf("digite a area: \n");
   scanf("%f", &área2);
   printf("digite o pib: \n");
   scanf("%f", &pib2);
   printf("digite o numero de pontos turisticos: \n");
   scanf("%d", &pontosturisticos2);

   // declaração da variaveis adcionais da cidade 2

   float pibpercapita2 = pib2 / população2;
   float densidadepop2 = população2 / área2;

   float densidadeinv2 = 1.0 / densidadepop2;

   float superpoder2 = população2 + área2 + pib2 + pontosturisticos2 + pibpercapita2 + densidadeinv2;

   // informações de dados da carta 2

   printf("\n---dados da segunda carta---\n");
   printf("o estado é: %s\n, a cidade é: %s\n, o codigo é: %s\n", estado2, cidade2, codigo2);
   printf("a população é: %lu\n", população2);
   printf("a área é: %f\n o pib é: %f\n", área2, pib2);
   printf("o numero de pontos turisticos é: %d\n", pontosturisticos2);
   printf("o pibpercapita é: %f\n a densidade populacional é: %f\n", pibpercapita2, densidadepop2);
   printf("o super poder é: %f\n", superpoder2);

   // inicio das comparações das cartas e saida de resultado

   printf("população1 > população2?: %d\n", população1 > população2);
   printf("área1 > área2?: %d\n", area1 > área2);
   printf("pib1 > pib2?: %d\n", pib1 > pib2);
   printf("a densidadepop1 > desidadepop2?: %d\n", densidadepop1 > densidadepop2);
   printf("o pibpercapita1 > pibpercapita2?: %d\n", pibpercapita1 > pibpercapita2);
   printf("o super1 > super2?: %d\n", superpoder1 > superpoder2);

   
   return 0;

}
