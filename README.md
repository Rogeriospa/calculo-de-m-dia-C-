#include<stdio.h>
main()
{
	char aluno;
	float notaa, notab, notac, media;
	
	printf("Digite o nome do aluno: ");
	scanf("%c", &aluno);
	printf("Digite o valor da prova A: ");
	scanf("%f", &notaa);
	printf("Digite o valor da prova B: ");
	scanf("%f", &notab);
	printf("Digite o valor da prova C: ");
	scanf("%f", &notac);
	
	notaa = notaa * 2;
	notab = notab * 3;
	notac = notac * 5;
	
	media = notaa + notab + notac / 3;
	
	printf("O nome do aluno e %c\n:", aluno);
	printf("A media foi %f\n", media);
}
