## **Senzor intenzity osvětlení**

Jako senzor intenzity osvětlení bylo vybráno nízkoenergetické čidlo VEML7700 od společnosti Vishay Semiconductors. Senzor v sobě integruje fotodiodu, nízkošumový zesilovač a 16bitový A/D převodník, což umožňuje měřit okolní osvětlení s rozlišením až 0.0042 lx v rozsahu od 0 do 140 000 lx. Tento rozsah je plně dostačující i pro venkovní měření při dopadu přímého slunečního světla, aniž by docházelo k saturaci čidla. Přenos naměřených dat je poté možný pomocí I2C rozhraní.

### Základní specifikace senzoru VEML7700

| Parametr | VEML7700 |
| :--- | :--- |
| **Výrobce** | Vishay Semiconductors |
| **Adresa zařízení** | `0x10` |
| **Napájecí napětí** | 2.5 až 3.6 V |
| **Měřicí rozsah** | 0 až 140 000 lx |
| **Měřicí rozlišení** | až 0.0042 lx / krok |
| **Spotřeba při vypnutí** | 0.5 µA |
| **Spotřeba při měření** | 2 až 45 µA |
| **Pracovní teplota** | -25 °C až +85 °C |
| **Rozhraní** | I²C |
| **Velikost pouzdra** | 6.8 × 2.35 × 3.0 mm |
| **Cena** | cca 27 Kč |

Pozn.: Uvedené hodnoty platí pro teplotu 25 °C. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spotřeba při měření se liší v závislosti na zvoleném režimu a frekvenci měření
