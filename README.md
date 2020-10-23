#include"volume.h"

int main()
{
	int jari;
	float volbol;
	printf("menghitung volume bola\n");
	printf("masukkan jari jari : ");
	scanf("%i", &jari);
	volbol=volumebola(jari);
	printf("volume bola :%.2f",volbol);
	getch();
	
}
