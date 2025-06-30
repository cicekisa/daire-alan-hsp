// Yarıçapı verilen dairenin alanını hesaplayan algoritmayı yazınız. (pi = 3.14)
# daire-alan-hsp

#include <stdio.h>
#define pi 3.14
int main() {
float yaricap = 0;
printf("dairenin yaricapini giriniz:");
scanf("%f",&yaricap);

float dairenin_alani = pi * (yaricap * yaricap) ; 
printf("dairenin alani: %f",dairenin_alani);

return 0;
}
