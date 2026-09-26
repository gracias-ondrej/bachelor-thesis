
### **Přehled spotřeby a doby měření senzorů meteostanice**

| Název periferie | Spotřeba při měření | Klidovová spotřeba | Doba měření |
| :--- | :--- | :--- | :--- |
| **VEML7700** | 45 μA | 0,5 μA | 25 ms |
| **SHT40** | 350 μA | 0,1 μA | 6.9 ms |
| **BMP390** | 660 μA (tlak) / 240 μA (teplota) | 1,5 μA | 69,5 ms |
| **SEN62** | 75 mA | 3,3 mA | 31 s |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecí napětí 3.3 V. <br>
>  [2] Spotřeba senzoru SEN62 dosahuje 3,3 mA, což je pro dlouhodobý provoz na baterii příliš vysoká hodnota a proto je nezbytné použití MOSFET tranzistoru pro tvrdé odpojení napájení. <br>
>  [3] Všechny uvedené hodnoty představují typické parametry pro nejvyšší použitelné rozlišení a přesnost jednotlivých senzorů. <br>
>  [4] Délka měření senzoru uvedená v tabulce neodpovídá specifikacím v datasheetu, kde je typický odběr 45 μA definován pro integrační dobu 100 ms. Domnívám se však, že ačkoliv dokumentace spotřebu pro 25ms interval explicitně neuvádí, nebude se okamžitý odběr od 100 ms varianty zásadně lišit. <br>
>  [5] Senzor BMP390 měří tlak i teplotu zvlášť, proto jsou hodnoty spotřeby pro tyto měření uvedeny zvlášť.

### **Přehled spotřeby modulu LoRa-E5**

| Modul | Klidová spotřeba | Spotřeba při běhu MCU | Spotřeba při vysílání |
| :--- | :--- | :--- | :--- |
| LoRa-E5 | 2,1 µA | 1,85 mA | 111 mA |

> **Poznámky:** <br>
>  [1] Spotřeba při běhu MCU byla stanovena pro frekvenci 16 MHz. <br>

### **Přehled velikosti výstupních dat senzorů**

| Název periferie | Velikost výstupních dat | Složení výstupních dat |
| :--- | :--- | :--- |
| **VEML7700** | 16 bitů | 16 bitů DATA |
| **SHT40** | 48 bitů | 32 bitů DATA + 16 bitů CRC |
| **BMP390** | 48 bitů | 48 bitů DATA |
| **SEN62** | 144 bitů | 96 bitů DATA + 48 bitů CRC
