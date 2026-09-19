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
| **Spotřeba při vypnutí** | 0.5 µA |
| **Spotřeba při měření** | 2 až 45 µA |
| **Pracovní teplota** | -25 °C až +85 °C |
| **Rozhraní** | I²C |
| **Velikost pouzdra** | 6.8 × 2.35 × 3.0 mm |
| **Cena** |  |

> **Poznámky:** <br>
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C. <br>
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
>  Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C. <br>
>  Hodnoty citlivosti a měřicího rozsahu jsou uvedeny pro konfiguraci GAIN = 1x. Toto minimální zesílení poskytuje maximální dynamický rozsah, který je nezbytný pro spolehlivé měření ve venkovním prostředí.
### **Související dokumentace** <br>
* [Datasheet AS7331](datasheets/datasheet_as7331.pdf)
