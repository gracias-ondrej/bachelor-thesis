
### **Přehled spotřeby a doby měření senzorů meteostanice**

| Senzor | Spotřeba při měření | Spotřeba při v klidu | Doba měření |
| :--- | :--- | :--- | :--- |
| **VEML7700** | 45 μA | 0,5 μA | 25 ms |
| **SHT40** | 2.4 μA | 0,1 μA | 7.2 ms |
| **BMP390** | 46.4 μA | 1,5 μA | 69,5 ms |
| **SEN62** | 75 mA | 3,3 mA | 30 s |

> **Poznámky:** <br>
>  [1] Uvedené hodnoty jsou stanoveny výrobcem pro teplotu okolí 25 °C a napájecím napětím 3.3V. <br>
>  [2] Spotřeba senzoru SEN62 dosahuje 3,3 mA, což je pro dlouhodobý provoz na baterii příliš vysoká hodnota a proto je nezbytné použití MOSFET tranzistoru pro tvrdé odpojení napájení. <br>
>  [3] Všechny uvedené hodnoty představují typické parametry pro nejvyšší použitelné rozlišení a přesnost jednotlivých senzorů.

### **Přehled spotřeby modulu LoRa-E5**

| Modul | Spotřeba při uspání | Spotřeba při běhu MCU | Spotřeba při vysílání |
| :--- | :--- | :--- | :--- |
| LoRa-E5 | 2,1 µA | 1,85 mA | 111 mA |

