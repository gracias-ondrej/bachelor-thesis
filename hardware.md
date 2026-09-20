## Senzor intenzity osvětlení

### Základní specifikace senzoru VEML7700

| **Parametr** | VEML7700 |
| :--- | :--- |
| **Výrobce** | Vishay Semiconductors |
| **Adresa zařízení** | `0x10` |
| **Velikost výstupních dat** | 16 bitů |
| **Napájecí napětí** | 2.5 až 3.6 V |
| **Měřicí rozsah** | 0 až 140 000 lx |
| **Měřicí rozlišení** | až 0.0042 lx |
| **Spotřeba při vypnutí** | až 0.5 µA |
| **Spotřeba při měření** | až 45 µA |
| **Pracovní teplota** | -25 °C až +85 °C |
| **Rozhraní** | I²C |
| **Velikost pouzdra** | 6.8 × 2.35 × 3.0 mm |
| **Cena** |  |

> **Poznámky:** <br>
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br>
>  Spotřeba při měření se liší v závislosti na zvoleném úsporném režimu (PSM) a frekvenci měření.

### **Související dokumentace** <br>
* [Datasheet VEML7700](datasheets/datasheet_veml7700.pdf) <br>
* [Application Note VEML7700](datasheets/application_note_veml7700.pdf)

<br>
<br>

## Senzor UV záření

### Základní specifikace senzoru AS7331 

| **Parametr**| AS7331 |
| :--- | :--- |
| **Výrobce** | ams OSRAM |
| **Adresa zařízení** | `0x74`,`0x75`,`0x76`,`0x77` |
| **Velikost výstupních dat** | 16 bitů |
| **Napájecí napětí** | 2.7 až 3.6 V |
| **Měřené složky** | UVA, UVB, UVC |
| **Měřicí rozsah UVA** | 3,49 × 10⁵ µW/cm² |
| **Citlivost UVA** | 0,188 counts/(µW/cm²) |
| **Měřicí rozsah UVB** | 3,86 × 10⁵ µW/cm² |
| **Citlivost UVB** | 0,170 counts/(µW/cm²) |
| **Měřicí rozsah UVC** | 1,69 × 10⁵ µW/cm² |
| **Citlivost UVC** | 0,388 counts/(µW/cm²) |
| **Spotřeba při vypnutí** | až 1 µA |
| **Spotřeba při čekání** | až 970 µA |
| **Spotřeba při měření** | až 2 mA |
| **Pracovní teplota** | -40 °C až +85 °C |
| **Velikost pouzdra** | 3.65 × 2.60 × 1.09 mm |
| **Rozhraní** | I²C |
| **Cena** |  |

> **Poznámky:** <br>
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br>
>  Hodnoty citlivosti a měřicího rozsahu jsou uvedeny pro konfiguraci GAIN = 1x. Toto minimální zesílení poskytuje maximální dynamický rozsah, který je nezbytný pro spolehlivé měření ve venkovním prostředí.

### **Související dokumentace** <br>
* [Datasheet AS7331](datasheets/datasheet_as7331.pdf) <br>

<br>
<br>

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
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br>
>  Senzor je vybaven integrovaným topným tělískem s volitelným výkonem (až 200 mW) pro odpaření zkondenzované vlhkosti.
>  Toto topné těleso není zohledněno v hodnotách uvedených v tabulce základních specifikací senzoru.

### **Související dokumentace** <br>
* [Datasheet SHT40](datasheets/datasheet_sht40.pdf)
* [Application Note SHT40](datasheets/application_note_sht40.pdf)

<br>
<br>

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
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecí napětí 3.3 V. <br>

### **Související dokumentace** <br>
* [Datasheet BMP390](datasheets/datasheet_bmp390.pdf) 


<br>
<br>

## Magnetometr

### Základní specifikace senzoru LIS2MDL

| **Parametr**| LIS2MDL |
| :--- | :--- |
| **Adresa zařízení** | `0x1E` |
| **Velikost výstupních dat** | 16 bitů|
| **Napájecí napětí** |  1.71 až 3.6 V |
| **Pracovní teplota** | -40 °C až +85 °C |
| **Spotřeba při měření** | až 120 µA |
| **Spotřeba při vypnutí** | až 1.5 µA|
| **Měřicí rozsah** | ±50 gauss |
| **Měřicí rozlišení** | 1.5 mgauss/LSB|
| **Přesnost měření** | 3 mgauss |
| **Velikost pouzdra** | 2.0 x 2.0 x 0.7 mm |
| **Rozhraní** | I²C, SPI |
| **Cena** |  |

> **Poznámky:** <br>
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecí napětí 2.5 V. <br>
>  Senzor navíc obsahuje zabudovaný teplotní snímač sloužící k teplotní kompenzaci v okolí samotného magnetometru

### **Související dokumentace** <br>
* [Datasheet LIS2MDL](datasheets/datasheet_lis2mdl.pdf) 

<br>
<br>

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
| **Velikost pouzdra** | 55.2 × 29.9 × 19.2 mm |
| **Rozhraní** | I²C |
| **Cena** |  |


> **Poznámky:** <br>
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C, napájecí napětí 3.3 V, vlhkost vzduchu 50 % a tlak 1013 mbar. <br>
>  Krátkodobé proudové špičky při měření dosahují až 190 mA
>  Senzor navíc obsahuje zabudovaný snímač teploty a vlhkosti sloužící ke kompenzaci vlhkosti a teploty v okolí samotného magnetometru


### **Související dokumentace** <br>
* [Datasheet SEN62](datasheets/datasheet_sen62.pdf) 
