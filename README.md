#include <stdio.h>
#include <locale.h>

int main(){
    setlocale(LC_ALL, "Portuguese");
    int valor[5], i, soma = 0, media;

    for (i=0; i<5; i++){
         printf("Qual o % do valor?\n", i+1);
         scanf("%d", &valor[i]);

         soma=soma+valor[i];

}
media = soma / 5;

printf("A média vale: %d\n", media);

for (i=0; i<5; i++){
    if (valor[i] < media){
       printf  ("\nSeu valor é menor que a média %d", valor[i]);

    }
     else{
        printf("\nSeu valor é maior que a média %d", valor[i]);
     }}
return 0:
}
