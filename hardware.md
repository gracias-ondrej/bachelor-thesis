## **Senzor intenzity osvětlení**

Jako senzor intenzity osvětlení byl vybrán nízkoenergetický snímač **VEML7700** od společnosti **Vishay Semiconductors**. Senzor v sobě integruje fotodiodu, nízkošumový zesilovač a 16bitový A/D převodník, což umožňuje měřit okolní osvětlení s rozlišením až **0.0042 lx** v rozsahu od **0 do 140 000 lx**. Tento rozsah je plně dostačující i pro venkovní měření při dopadu přímého slunečního světla, aniž by docházelo k saturaci snímače. Přenos naměřených dat je poté možný pomocí **I²C** rozhraní.

### Základní specifikace senzoru VEML7700

| Parametr | VEML7700 |
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
| **Cena** | cca 27 Kč |

Pozn.: Uvedené hodnoty platí pro teplotu 25 °C. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spotřeba při měření se liší v závislosti na zvoleném režimu a frekvenci měření

### Datasheety a dokumentace
* [Datasheet VEML7700](datasheets/datasheet_veml7700.pdf)
* [Application Note VEML7700](datasheets/application_note_veml7700.pdf)

<br>
<br>

## **Senzor UV záření**

O měření UV záření se stará snímač **AS7331** od společnosti **ams OSRAM**. Měří tři různé složky ultrafialového záření, a to UVA, UVB a UVC, každé pomocí své diody. Součástí obvodu je integrovaný 24bitový A/D převodník, který převádí naměřený analogový signál na digitální podobu. Přenos naměřených dat je zajištěn **I²C** rozhraním s možností volby mezi čtyřmi adresami zařízení, což umožňuje připojení až čtyř senzorů AS7331 na jednu společnou sběrnici.

### Základní specifikace senzoru AS7331 

### Datasheety a dokumentace
