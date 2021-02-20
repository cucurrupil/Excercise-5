#include <stdio.h>
#include <conio.h>

//area y perimetro de cuadrado
int a,p,l;

int main(void){
	printf("Ingrese un lado del cuadrado en centimetros\n");
   scanf("%d", &l);
	p = l * 4;
	a = l * 2;
	printf("El perimetro de tu cuadrado es de %d cm y su area es de %d cm^2",p,a);
	getch();
	return 0;
}
