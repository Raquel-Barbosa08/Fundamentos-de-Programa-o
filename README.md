# Fundamentos-de-Programa-o
Questôes de FUP
SOMA SIMPLES DE DOIS INTEIROS 
#include <stdio.h>

int main(){
    int a , b;
    scanf("%d %d", &a ,&b);
    printf("%d", a+b);
return 0;
}
/////////////////////////////////////////////////
Média Aritmética de Dois Inteiros 
#include <stdio.h>

int main(){
    int m1;
    int m2;
    float media;
    scanf("%d", &m1);
    scanf("%d", &m2);
    media = (m1+m2)/2.0;
    printf("%f",media);
    return 0;
}
//////////////////////////////////////////////////
Conversor de unidade de temperatura Celsius (ºC) para Fahrenheit (ºF) 
#include <stdio.h>

int main(){
    float tc;
    scanf("%f", &tc);
    float tf = (tc * 9/5) + 32 ;
    printf("%f", tf);
    return 0;
}
///////////////////////////////////////////////////
FORMULA DO NÚMERO DA JUVENTUDE 
#include <stdio.h>

int main(){
    float peso,alt;
    int idade,anonasc,dianasc;
    float formula;
    scanf("%f %f ",&peso,&alt );
    scanf("%d %d %d", &idade,&anonasc,&dianasc);
    formula = ((peso+alt)/idade + anonasc) *dianasc;
    printf("%f" , formula);
    return 0;
}
//////////////////////////////////////////////////
FORMULA DO NÚMERO DA JUVENTUDE VERSÃO 2 
#include <stdio.h>

int main(){
    float peso,alt;
    int idade,anonasc,dianasc;
    float formula;
    scanf("%f %f ",&peso,&alt );
    scanf("%d %d %d", &idade,&anonasc,&dianasc);
    formula = (((peso+alt)/idade + anonasc) *dianasc - 33)* (idade + 7);
    printf("%f" , formula);
    return 0;
}
/////////////////////////////////////////////////
Conversor de unidade de temperatura 
#include <stdio.h>

int main(){
    float C,F;
    scanf("%f-%f",&C,&F);
    float F1 = (C*9/5)+32;
    float C1 = 5*(F-32)/9;
    printf("%.2f C = %.2f F\n",C, F1);
    printf("%.2f F = %.2f C",F, C1);
    return 0;
    
}
////////////////////////////////////////////////
Conversor de unidade de temperatura Celsius (ºC) para Fahrenheit (ºF) 
#include <stdio.h>

int main(){
float gc;
scanf ("%f", &gc);
float fh= (gc*9/5)+32;
printf ("A temperatura de hoje e %.0fC, que equivale a %.2fF.",gc,fh);
}
/////////////////////////////////////////////////
FORMATANDO DATAS 
#include <stdio.h>

int main(){
    int dia, mes , ano, idade ;
    scanf("%d/%d/%d %d" , &dia, &mes,&ano,&idade);
    printf("Voce nasceu no dia %d do mes %d no ano %d e hoje tem %d anos.", dia,mes,ano,idade);
}
//////////////////////////////////////////////////
Tempo 
#include <stdio.h>

int main(){
    int S, H, M, resto;
    scanf("%d" , &S);
    H = S / 3600;
    resto = S % 3600;
    M = resto / 60;
    S = resto % 60;
    printf ("%d:%d:%d",H, M, S);
    return 0;
}
/////////////////////////////////////////////////
Teorema da Divisao
#include <stdio.h>

int main (){
    int num1;
    int num2;
    scanf ("%d/%d", &num1, &num2);
    int q = num1/num2;
    int resto = num1%num2;
    printf ("Na divisao de %d por %d, o quociente e %d e o resto da divisao e %d",num1,num2,q,resto);
}
É O NUMERO 3? 
#include <stdio.h>

int main(){
    int num;
    scanf("%d",&num);
    if(num==3){
        printf("SIM");
    }
 return 0;   
 }
///////////////////////////////////////////
MAIOR OU IGUAL A 16? 
#include <stdio.h>

int main(){
    int num;
    scanf("%d",&num);
    
    if(num>=16){
        printf("SIM");
    }
    return 0;
}
////////////////////////////////////////////
MULTIPLO DE 7? 
#include <stdio.h>

int main(){
    int num;
    scanf("%d",&num);
    int mul = num%7;
    
    if(mul==0){
        printf("SIM");
    }
    return 0;
}
///////////////////////////////////////////
PAR ou IMPAR 
#include <stdio.h>

int main(){
    int num;
    scanf("%d",&num);
    
    if(num%2 == 0){
        printf("PAR");
    }
    if(num%2 == 1){
        printf("IMPAR");
    return 0;
}

return 0;
}
///////////////////////////////////////////
#include <stdio.h>

int main(){
    int num,num2;
    scanf("%d %d",&num,&num2);
 
    
    if(num>num2 )  {
        printf("%d",num);
    }
        else{
            printf("%d",num2);
     
    }
    return 0;
}







































