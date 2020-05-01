    #include <stdio.h>
    #include <stdlib.h>

    int main() {
    
    float yakittuketimi;
    float yakitfiyati;
    float toplamyol;
    float yakitmaliyeti;

    printf("Km basina yakit tuketimi (lt): ");
    scanf("%f", &yakittuketimi);

    printf("1 lt yakitin fiyati (TL): ");
    scanf("%f", &yakitfiyati);

    printf("Aracin katettigi toplam yol (km): ");
    scanf("%f", &toplamyol);

    printf("-----------------------------\n");

    yakitmaliyeti= yakittuketimi*yakitfiyati*toplamyol;

    printf("Toplam yakit maliyeti: %f TL", yakitmaliyeti);

    return 0; }
