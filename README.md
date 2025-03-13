#include<stdio.h>
#include<stdlib.h>

int main() {
   //Declaração das variáveis para guardar os valores
   int dividendo;
   int divisor;
   
   //Imprime mensagem para a inserção do primeiro valor
   printf("Digite o valor do dividendo:");
   //Guarda o valor digitado pelo usuário na variável dividendo
   scanf("%d", &dividendo);
   
   //Imprime mensagem para a inserção do segundo valor
   printf("\nDigite o valor do divisor:");
   //Guarda o valor digitado pelo usuário na variável divisor
   scanf("%d", &divisor);   
   
   //Verifica se o valor do divisor é igual a zero
   if (divisor == 0) {
      //Imprime o valor -1 caso o divisor seja zero
      printf("-1\n");
   }
   //Verifica se o valor do cálculo da divisão é negativo
   else if ((dividendo / divisor < 0)) {
      //Imprime o valor 0 caso o resultdo da divisão seja negativo
      printf("Valor encontrado: 0\n");
   }
   else {
      //Como o divisor não é zero e o cálculo não é negativo, imprime o resultado da divisão
      printf("Valor calculado: %d \n", (dividendo / divisor));
   }
   
   system("PAUSE");
}
