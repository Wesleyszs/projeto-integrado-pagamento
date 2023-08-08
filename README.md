![im4](https://github.com/Wesleyszs/projeto-integrado-pagamento/assets/122413661/c791ee9e-42f5-4e38-a782-5c006308a408)
![im1](https://github.com/Wesleyszs/projeto-integrado-pagamento/assets/122413661/ec9b1374-e022-4415-85dc-9a1255849238)
 #include <stdio.h>

int main() {
int opcao;
float valor, valor_Juros , valor_de;
printf ("aluno - francisco wesley souza de abreu \n");
printf("Projeto integrado professor gehard saboia\n");

printf("Bem-vindo(a)!\n\n");
printf("Digite o valor da compra: R$ ");
scanf("%f", &valor);
printf("------------------------------------------\n");
printf("\nEscolha uma opcao de pagamento:\n");
printf("1 - A vista em dinheiro ou pix (10%%)\n");
printf("2 - A vista no cartao de credito (5%%)\n");
printf("3- Parcelado 2x sem juros\n");
printf("4 - Parcelado em 3 com juros (10%%)\n");
printf("5 - sair\n");
printf("Opcao: \n");
printf("------------------------------------------\n");
scanf("%d", &opcao);

switch (opcao) {
case 1:
valor_Juros = valor * 0.9;
printf("\nValor final da compra: R$ %.2f\n", valor_Juros);
 break;
 case 2:
 	valor_de = (valor*5)/100;
 printf("\nValor do desconto s: R$ %.2f\n", valor_de);
 printf("Valor final da compra: R$ %.2f\n", valor-valor_de);
break;
case 3:

 printf("\nValor das parcelas: 2x R$ %.2f\n", valor/2);
 printf("Valor final da compra: R$ %.2f\n", valor);
break;
case 4 :
valor_Juros = valor * 1.10;
	 printf("\nValor das parcelas com o juros: R$ %.2f\n", valor_Juros/3);
 printf ("Valor final da compra: R$ %.2f\n",valor_Juros);
 break;
case 5:
 default:

printf("\nOpcao invalida!\n");


  }


}![Uploading im2.png…]()
![Uploading im3.png…]()
