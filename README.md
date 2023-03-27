#include <stdio.h>
		
int main(void)
{
	int salario, salarioBonus;
	
	printf("Insira o salario do individuo para saber se ele recebera um bonus:\n\n");
	
	printf("Salario do individuo:\n\n");
	scanf("%i", &salario);
	
	salarioBonus = salario + 1000;
	
	printf("salario = %i  \n\n", salario);
	
	
	if (salario < 100000){
		printf("Ganhou bonus de 1000 no salario \n\n");
	
		
		} else {
		printf("Nao ganhou bonus\n\n");
	}

	
if (salario < 100000){
		printf ("o salario com bonus %i + 1000 eh %i\n\n", salario, salarioBonus);
	}else{
		printf (" \n", salario, salarioBonus);
	}
 }
