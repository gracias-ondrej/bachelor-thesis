## **Senzor intenzity osvětlení**

Jako senzor intenzity osvětlení byl vybrán nízkoenergetický snímač **VEML7700** od společnosti **Vishay Semiconductors**. Senzor v sobě integruje fotodiodu, nízkošumový zesilovač a 16bitový A/D převodník, což umožňuje měřit okolní osvětlení s rozlišením až **0.0042 lx** v rozsahu od **0 do 140 000 lx**. Tento rozsah je plně dostačující i pro venkovní měření při dopadu přímého slunečního světla, aniž by docházelo k saturaci snímače. Přenos naměřených dat je poté možný pomocí **I²C** rozhraní.

### Základní specifikace senzoru VEML7700

| :--- | :--- |
| **Parametr** | VEML7700 |
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
| **Cena** | cca 27 Kč |

Pozn.: Uvedené hodnoty platí pro teplotu 25 °C. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spotřeba při měření se liší v závislosti na zvoleném režimu a frekvenci měření

### Datasheety a dokumentace
* [Datasheet VEML7700](datasheets/datasheet_veml7700.pdf)
* [Application Note VEML7700](datasheets/application_note_veml7700.pdf)

<br>
<br>

## **Senzor UV záření**

O měření UV záření se stará snímač **AS7331** od společnosti **OSRAM**. Měří tři různé složky ultrafialového záření UVA, UVB a UVC, každé pomocí své diody. Součástí obvodu je integrovaný 24bitový A/D převodník, který zajišťuje vysokou citlivost a dynamický rozsah, aby senzor dokázal detekovat i nepatrné změny záření. Přenos naměřených dat je zajištěn **I²C** rozhraním s možností volby mezi čtyřmi adresami zařízení, což umožňuje připojení až čtyř senzorů AS7331 na jednu společnou sběrnici.

### Základní specifikace senzoru AS7331 

| :--- | :--- |
| **Parametr**| AS7331 |
| **Výrobce** | OSRAM |
| **Adresa zařízení** | `0x74` `0x75` `0x76` `0x77` |
| **Velikost výstupních dat** | 24 bitů |
| **Napájecí napětí** | 2.7 až 3.6 V |
| **Měřené složky** | UVA, UVB, UVC |
| **Měřicí rozsah UVA** | $3,49 \cdot 10^5 \text{ µW/cm}^2$ |
| **Citlivost UVA** | $0,188 \text{ counts}/(\text{µW/cm}^2)$ |
| **Měřicí rozsah UVB** | $3,86 \cdot 10^5 \text{ µW/cm}^2$ |
| **Citlivost UVB** | $0,170 \text{ counts}/(\text{µW/cm}^2)$ |
| **Měřicí rozsah UVC** | $1,69 \cdot 10^5 \text{ µW/cm}^2$ |
| **Citlivost UVC** | $0,388 \text{ counts}/(\text{µW/cm}^2)$ |
| **Spotřeba při vypnutí** | 1 µA |
| **Spotřeba při měření** | 2 mA |
| **Pracovní teplota** | -40 °C až +85 °C |
| **Velikost pouzdra** | 6.8 × 2.35 × 3.0 mm |
| **Rozhraní** | I²C |


### Datasheety a dokumentace
