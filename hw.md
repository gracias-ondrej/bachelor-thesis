<br>
# Specifikace použitých senzorů
<br>

## Senzor intenzity osvětlení

### Základní specifikace senzoru VEML7700

| **Parametr** | VEML7700 |
| :--- | :--- |
| **Výrobce** | Vishay Semiconductors |
| **Adresa zařízení** | `0x10` |
| **Velikost výstupních dat** | 16 bitů |
| **Napájecí napětí** | 2.5 až 3.6 V |
| **Pracovní teplota** | -25 °C až +85 °C |
| **Spotřeba při vypnutí** | až 0.5 µA |
| **Spotřeba při měření** | až 45 µA |
| **Měřicí rozsah** | 0 až 140 000 lx |
| **Měřicí rozlišení** | až 0.0042 lx |
| **Rozhraní** | I²C |
| **Velikost pouzdra** | 6.8 × 2.35 × 3.0 mm |
| **Cena** |  |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br><br>
>  [2] Při venkovním použití a vystavení přímému slunci je pro zamezení saturace zvoleno nastavení zesílení na hodnotu ALS gain x 1/8 a současně integrační čas 25 ms, přičemž výsledné rozlišení odpovídá hodnotě 2.1504 lx.<br><br>
>  [3] Při probuzení ze stavu vypnutí je nutné před prvním čtením dat dodržet čekací dobu minimálně 2.5 ms pro ustálení vnitřního oscilátoru.

## Senzor vlhkosti a teploty

### Základní specifikace senzoru SHT40

| **Parametr**| SHT40 |
| :--- | :--- |
| **Výrobce** | SENSIRION |
| **Adresa zařízení** | `0x44` |
| **Velikost výstupních dat** | 16 bitů + 8 bitů (CRC) |
| **Napájecí napětí** | 1.08 až 3.6 V |
| **Spotřeba při čekání** | až 3.4 µA |
| **Spotřeba při měření** | až 500 µA |
| **Měřicí rozsah teploty** | -40 až 125 °C|
| **Měřicí rozlišení teploty** | 0.01 °C|
| **Přesnost měření teploty** | ±0.2 °C|
| **Měřicí rozsah vlhkosti** | 0 až 100 %|
| **Měřicí rozlišení vlhkosti** | 0.01 %|
| **Přesnost měření vlhkosti** | ±1.8 %|
| **Pracovní teplota** | -40 °C až +125 °C |
| **Velikost pouzdra** | 1.5 × 1.5 × 0.5 mm |
| **Rozhraní** | I²C |
| **Cena** |  |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br><br>
>  [2] Senzor je vybaven integrovaným topným tělískem s volitelným výkonem (až 200 mW) pro odpaření zkondenzované vlhkosti. <br><br>
>  [3] Toto topné těleso není zohledněno v hodnotách uvedených v tabulce základních specifikací senzoru.

## Senzor tlaku

### Základní specifikace senzoru BMP390

| **Parametr**| BMP390 |
| :--- | :--- |
| **Výrobce** | BOSCH |
| **Adresa zařízení** | `0x77` |
| **Velikost výstupních dat** | 48 bitů|
| **Napájecí napětí** |  1.65 až 3.6 V |
| **Spotřeba při vypnutí** | až 1.5 µA|
| **Spotřeba při měření teploty** | až 320 µA |
| **Spotřeba při měření tlaku** | až 730 µA |
| **Měřicí rozsah teploty** | -40 až +85 °C|
| **Měřicí rozlišení teploty** | 0.00015 °C|
| **Přesnost měření teploty** | ±0.5 °C|
| **Měřicí rozsah tlaku** | 300 až 1250 hPa|
| **Měřicí rozlišení tlaku** | 0.085 Pa|
| **Přesnost měření tlaku** | ±0.33 hPa|
| **Pracovní teplota** | -40 °C až +85 °C |
| **Velikost pouzdra** | 2.0 x 2.0 x 0.75 mm |
| **Rozhraní** | I²C, SPI |
| **Cena** |  |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecí napětí 3.3 V. <br>

## Senzor prachových částic

### Základní specifikace senzoru SEN62

| **Parametr**| SEN62 |
| :--- | :--- |
| **Adresa zařízení** | `0x6B` |
| **Velikost výstupních dat** | 144 bitů|
| **Napájecí napětí** |  3.15 až 3.6 V |
| **Pracovní teplota** | -10 °C až +60 °C |
| **Spotřeba při čekání** | 3.3 mA |
| **Spotřeba při měření** | 90 mA |
| **Měřené složky** | PM1, PM2.5, PM4, PM10 |
| **Měřicí rozsah** | 0 až 1000 μg/m3 |
| **Přesnost PM1 a PM2.5 (0 až 100 µg/m³)** | ±(5 µg/m³ + 5 % z naměřené hodnoty) |
| **Přesnost PM1 a PM2.5 (100 až 1000 µg/m³)** | ±10 % z naměřené hodnoty |
| **Přesnost PM4 a PM10 (0 až 100 µg/m³)** | ±25 µg/m³ |
| **Přesnost PM4 a PM10 (100 až 1000 µg/m³)** | ±25 % z naměřené hodnoty |
| **Velikost pouzdra** | 55.2 × 26.6 × 21.3 mm |
| **Rozhraní** | I²C |
| **Cena** |  |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C, napájecí napětí 3.3 V, vlhkost vzduchu 50 % a tlak 1013 mbar. <br><br>
>  [2] Krátkodobé proudové špičky při měření dosahují až 190 mA<br><br>
>  [3] Senzor navíc obsahuje zabudovaný snímač teploty a vlhkosti sloužící ke kompenzaci vlhkosti a teploty v okolí. <br><br>
>  [4] Při probuzení ze stavu vypnutí je nutné před prvním čtením dat dodržet čekací dobu minimálně 30 s.

## Senzor rychlosti větru

### Základní specifikace senzoru WH-SP-WS01

| **Parametr**| WH-SP-WS01 |
| :--- | :--- |
| **Měřící rozsah** | 0 až 160km/h |
| **Měřící rozlišení** | 2.4 km/h |
| **Přesnost** | ± 1m/s v rozsahu do 10m/s <br> ± 10% v rozsahu nad 10m/s|
| **Velikost pouzdra** | 150 × 80 × 170 mm |
| **Rozhraní** | RJ11 (2 vodiče) |
| **Cena** |  |

## Senzor srážek

### Základní specifikace senzoru HS-WH-SP-RG

| **Parametr**| HS-WH-SP-RG |
| :--- | :--- |
| **Měřící rozsah** | 0 – 9999mm |
| **Měřící rozlišení** | 0,3mm v rozsahu do 1000mm <br> 1mm v rozsahu nad 1000mm |
| **Přesnost** | 10% |
| **Velikost pouzdra** | 170 × 110 × 80 mm |
| **Rozhraní** | RJ11 (2 vodiče) |
| **Cena** |  |
<br>
# Spotřeba meteostanice
<br>
### **Přehled spotřeby a doby měření senzorů meteostanice**

| Název periferie | Spotřeba při měření | Klidová spotřeba | Doba měření |
| :--- | :--- | :--- | :--- |
| **VEML7700** | 45 μA | 0,5 μA | 25 ms |
| **SHT40** | 350 μA | 0,1 μA | 6.9 ms |
| **BMP390** | 660 μA (tlak) / 240 μA (teplota) | 1,5 μA | 69,5 ms |
| **SEN62** | 75 mA | 3,3 mA | 90 s |

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

### **Přehled maximální spotřeby (peak) senzorů meteostanice**

| Název periferie | Maximální spotřeba |
| :--- | :--- |
| **VEML7700** | 45 µA |
| **SHT40** | 500 µA |
| **BMP390** | 730 µA |
| **SEN62** | 190 mA |
| **LoRa-E5** | 111 mA |
| **Celková spotřeba** | 302.275 mA |

> **Poznámky:** <br>
>  [1] Maximální spotřeba pro senzor SHT40 je definována bez výhřevu tepelného článku a pro snímač VEML7700 výrobce neuvádí maximální hodnotu proudu, tudíž byla použita hodnota typická. <br><br>
>  [2] Maximální spotřeba anenometru, sražkoměru a ostatních obvodů v návrhu nejsou započítány z důvodu zanedbatelné velikosti spotřeby a také z důvodu chybějících hodnot potřebných součástek.

<br>
# Definování komunikace
<br>

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
| **ADC převodník** | 8 bitů | Kapacita baterie |

> **Poznámky:** <br>
>  [1] Hodnoty v tabulce udávají maximální velikost surových dat, data se budou ještě v MCU upravovat. Tabulka slouží pouze jako hrubý odhad worst case scénáře. <br><br>
>  [2] U mechanických senzorů, tudíž srážkoměr a anenometr, budou odesílány hodnoty počtu jednotlivých sepnutí,které se následně zpracují na serveru. Tím se ušetří na množství potřebných bitů. <br><br>
>  [3] Maximální celkový přenos dat (payload) bude tudíž 160 bitů (20 bytů).
 
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
https://www.etsi.org/deliver/etsi_en/300200_300299/30022002/03.03.01_60/en_30022002v030301p.pdf

> **Poznámky:** <br>
>  [1] Síť The Thing Network stanovuje denní limity na 30 sekund vysílacího času a maximálně 10 příchozích zpráv za den na jedno zařízení. <br><br>
>  [2] Dle nařízení je také regulován duty cycle (poměr doby vysílání ku klidu) a to na maximální hodnotu 1%. <br><br>
>  [3] Počet zpráv a doba vysílání závisí primárně na SF (spreading factor). Změna velikosti dat (payload) nemá v porovnání s ním zásadní vliv, přesto je potřeba ji optimalizovat na minimum. <br><br>
>  [4] Tato tabulka znázorňuje worst case scénář, kdy se posílá maximální množství dat. <br><br>
>  [5] Z tabulky je očividné, že se bude muset pro každý SF zvolit odpovídající harmonogram odesílání. 

### **Přehled harmonogramů vysílání**

| Spreading Factor || Doba vysílání krátké zprávy | Velikost odesílaných dat | Interval mezi zprávami | Počet možných zpráv za 24h || Doba vysílání dlouhé zprávy | Velikost odesílaných dat | Interval mezi zprávami | Počet možných zpráv za 24h || Celková doba přenosu za den |
| :--- | :--- | :--- |:--- | :--- | :--- | :--- |:--- |:--- |:--- |:--- |:--- |:--- |
| **SF7** || 56.6 ms | 72 bitů | 5 min | 240 zpráv || 71.9 ms | 160 bitů | 30 min | 48 zprávy || 17,04 s |
| **SF8** || 102.9 ms | 72 bitů | 10 min | 96 zpráv || 133.6 ms | 160 bitů | 30 min | 48 zprávy || 16,29 s |
| **SF9** || 205.8 ms | 72 bitů | 15 min | 72 zpráv || 246.8 ms | 160 bitů | 60 min | 24 zprávy || 20,74 s |
| **SF10** || 370.7 ms | 72 bitů | 25 min | 48 zpráv || 452.6 ms | 160 bitů | 60 min | 24 zprávy || 28,66 s |
| **SF11** || ~~741.4 ms~~ | ~~72 bitů~~ | ~~60 min~~ | ~~0 zpráv~~ || 987.1 ms | 160 bitů | 60 min | 24 zprávy || 23,69 s |
| **SF12** || ~~1482.8 ms~~ | ~~72 bitů~~ | ~~90 min~~ | ~~0 zpráv~~ || 1810.4 ms | 160 bitů | 90min | 16 zprávy || 28,97 s |

