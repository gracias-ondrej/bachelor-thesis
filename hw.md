
### **Přehled spotřeby a doby měření senzorů meteostanice**

| Název periferie | Spotřeba při měření | Klidovová spotřeba | Doba měření |
| :--- | :--- | :--- | :--- |
| **VEML7700** | 45 μA | 0,5 μA | 25 ms |
| **SHT40** | 350 μA | 0,1 μA | 6.9 ms |
| **BMP390** | 660 μA (tlak) / 240 μA (teplota) | 1,5 μA | 69,5 ms |
| **SEN62** | 75 mA | 3,3 mA | 31 s |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecí napětí 3.3 V. <br><br>
>  [2] Spotřeba senzoru SEN62 dosahuje 3,3 mA, což je pro dlouhodobý provoz na baterii příliš vysoká hodnota a proto je nezbytné použití MOSFET tranzistoru pro tvrdé odpojení napájení. <br><br>
>  [3] Všechny uvedené hodnoty představují typické parametry pro nejvyšší použitelné rozlišení a přesnost jednotlivých senzorů. <br><br>
>  [4] Délka měření senzoru uvedená v tabulce neodpovídá specifikacím v datasheetu, kde je typický odběr 45 μA definován pro integrační dobu 100 ms. Domnívám se však, že ačkoliv dokumentace spotřebu pro 25ms interval explicitně neuvádí, nebude se okamžitý odběr od 100 ms varianty zásadně lišit. <br><br>
>  [5] Senzor BMP390 měří tlak i teplotu zvlášť, proto jsou hodnoty spotřeby pro tyto měření uvedeny zvlášť.

### **Přehled spotřeby modulu LoRa-E5**

| Modul | Klidová spotřeba | Spotřeba při běhu MCU | Spotřeba při vysílání |
| :--- | :--- | :--- | :--- |
| LoRa-E5 | 2,1 µA | 1,85 mA | 111 mA |

> **Poznámky:** <br>
>  [1] Spotřeba při běhu MCU byla stanovena pro frekvenci 16 MHz.

### **Přehled velikosti výstupních dat ze senzorů**

| Název periferie | Velikost výstupních dat | Složení výstupních dat |
| :--- | :--- | :--- |
| **VEML7700** | 16 bitů | 16 bitů DATA |
| **SHT40** | 48 bitů | 32 bitů DATA + 16 bitů CRC |
| **BMP390** | 48 bitů | 48 bitů DATA |
| **SEN62** | 144 bitů | 96 bitů DATA + 48 bitů CRC

> **Poznámky:** <br>
>  [1] Mechanické senzory (srážkoměr a anemometr) nejsou v této tabulce zahrnuty, jelikož jejich výstupem je impulz, který čítá MCU.

### **Přehled velikosti odesílaných dat (Payload)**

| Název periferie | Velikost odesílaných dat | Složení výstupních dat |
| :--- | :--- | :--- |
| **VEML7700** | 16 bitů | Jas |
| **SHT40** | 32 bitů | Teplota + vlhkost |
| **BMP390** | 24 bitů | Tlak |
| **SEN62** | 64 bitů | Množství prachových částic (PM1.0, PM2.5, PM4.0, PM10.0) |
| **WH-SP-WS01** | 8 bitů | Rychlost větru |
| **HS-WH-SP-RG** | 8 bitů | Množství srážek |

> **Poznámky:** <br>
>  [1] Hodnoty v tabulce udávají maximální velikost surových dat, data se budou ještě v MCU upravovat.

### **Přehled doby vysílání**

| Spreading Factor | Doba vysílání | Počet možných zpráv za 24h | Interval mezi zprávami
| :--- | :--- | :--- |:--- |
| **SF7** | 71.9 ms | 417 zpráv | 3 min a 30 s |
| **SF8** | 133.6 ms | 224 zpráv | 6 min a 26 s |
| **SF9** | 246.8 ms | 121 zpráv | 11 min a 54 s |
| **SF10** | 452.6 ms | 66 zpráv | 21 min a 49 s |
| **SF11** | 987.1 ms | 30 zpráv | 48 min |
| **SF12** | 1810.4 ms | 16 zpráv | 1 hod a 30 min |

https://www.thethingsnetwork.org/airtime-calculator

> **Poznámky:** <br>
>  [1] Síť The Thing Network stanovuje denní limity na 30 sekund vysílacího času a maximálně 10 příchozích zpráv za den na jedno zařízení.
