# Idade-em-dias

#include <stdio.h>
  
int main() {
  
int i,sobra;
    int ano,mes, dia;
  
    
    scanf("%d",&i);
  
    sobra = i;
    ano = sobra/365;
    sobra= sobra%365;
     
    mes = sobra/30;
    sobra= sobra%30;
  
    dia = sobra/1;
    sobra = sobra%1;
  
 
    printf("%d ano(s)\n",ano);
    printf("%d mes(es)\n",mes);
    printf("%d dia(s)\n",dia);
 
  
    return 0;
}
