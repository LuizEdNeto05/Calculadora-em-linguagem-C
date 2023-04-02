#include <stdio.h>
#include <stdlib.h>

int main() {
	int escolha;
	float a, b, c;
	
	while(1){
	printf("Escolha:\n 1- para adicao\n 2- para subtracao\n 3- para multiplicacao\n 4- para divisao\n");
	
	scanf("%d", &escolha);
	system ("cls");
	switch(escolha){
	
	while(1){
	
	case 1://usuario escolheu adicao
	printf("Digite o valor de a\n");
	scanf("%f", &a);
	printf("Digite o valor de b\n");
	scanf("%f", &b);
	c = a+b;
	printf("A soma entre a e b eh: %.1f\n", c);
     break;
     
	 case 2://Usuario escolheu subtracao
    printf("Digite o valor de a\n");
    scanf("%f", &a);
    printf("Digite o valor de b\n");
    scanf("%f", &b);
	c = a-b;
	printf("A subtracao entre a e b eh: %.1f\n", c);   
	break;
	
	case 3://Usuario escolheu multiplicacao
	printf("Digite o valor de a\n");
	scanf("%f", &a);
	printf("Digite o valor de b\n");
	scanf("%f", &b);
	c = a*b;
	printf("a vezes b eh: %.1f\n", c);
		break;
		
	case 4://Usuario escolheu divisao
		printf("Digite o valor de a\n");
		scanf("%f", &a);
		printf("Digite o valor de b\n");
		scanf("%f", &b);
		c = a/b;
		printf("a divisao de a por b eh: %.1f\n", c);
		break;
		} 
		printf("1) Fazer outra operacao\n2) Sair\n");
		scanf("%i", &escolha);
		
		
}
  if(escolha == 1){
  	system ("cls");
		}else if(escolha == 2){
			break;
		}
}
	return 0;
}
