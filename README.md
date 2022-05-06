//Exercicio-Triangulo
Formas de Triangulo
#include <stdlib.h>

int main (){
    int a,b,c;
    
    printf ("Digite três medidas: ");
    scanf("%d%d%d", &a, &b, &c);
    
    if (a +b >c && a +c>b&&b+c>a){
        printf("As 3 medidas formam um triangulo!!\n");
        if (a == b && a == c)
            printf("Forma-se um triangulo Equilatero\n");
        else
            if(a==b || a ==c || b == c)
              printf("Forma-se um triangulo Isosceles\n");
            else
              printf("Forma-se um triangulo Escaleno\n");
    }
    else
        printf("As 3 medidas não formam um triângulo!!\n");
        
        return 0;
}
