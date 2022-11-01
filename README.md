# algoritmo-f
Taxi //

#include <stdio.h>
#include <math.h>
float kmhs,tempo,qtdlitros;

int main(){
    printf("Quantas horas a viagem durou? ");
    scanf("%f",&tempo);
    printf("\nQual foi a media de velocidade? ");
    scanf("%f",&kmhs);
    kmhs=kmhs*tempo;
    printf("\n-O tempo de viagem foi %.0fH00",tempo),
    printf("\n-A qtd de kms percorridos foram %.0fkm/h\n",kmhs);
    qtdlitros=kmhs/12;
    printf("\nos kms percorridos foram %.0fkm/h\nE o tempo gasto foi %.0fH00",kmhs,tempo);
    printf("\nA qtd de litros necessario para a viagem foi de %.3f",qtdlitros);
    
    
    return 0;
}
