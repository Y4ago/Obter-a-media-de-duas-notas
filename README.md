// Obter a media de duas notas de um aluno - Language Dev C++.

#include<stdio.h>

int main()
{

  float n1, n2, med;

  printf("Digite uma nota: ", n1);
  scanf("%f", &n1);
  printf("Digite a segunda nota: ", n2);
  scanf("%f", &n2);
  
  med = (n1 + n2 ) / 2;
  
  printf("\n A media das notas e: %.2f ", med);

}
