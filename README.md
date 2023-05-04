# Disseny Placa Pr&#224;ctica 5

>**Autors:** J.L. Soler, J. Canals, J.D. Prades, M. L&#243;pez

>**Versi&#243; Curs 2022/2023**

----------

## Objectiu

>PCB per practicar la soldadura de diferents tipus de components, i el test i verificaci&#243; de muntatges.


## Requisits / Especificacions

* Alimentaci&#243; 12V, regulada 5V

* Microcontrolador PIC18

* Polsadors (2x)

* Indicadors LED (2x)

* Comunicacions CAN

* Driver motor

* Sensor humitat-temperatura

* Interfície d'expansió MIKROE


## Components

| Descripci&#243; | Ref | Package |Datasheet | Prove&#239;dor | Preu | Unitats |
| --- | --- | --- | --- | ---| --- | --- |
| Microcontrolador | PIC18F26Q83-I/SS | SOIC-28 |[datasheet](https://www.mouser.es/datasheet/2/268/PIC18F27_47_57Q83_Preliminary_Data_Sheet_40002265B-2887591.pdf) | [Mouser](https://www.mouser.es/c/?q=PIC18F27Q83-I%2FSO)| 2,17&euro;| 1x |
| XTAL-Ressonador | CSTCR7M99G53-R0 | SMD |[Datasheet](https://www.mouser.es/datasheet/2/281/p16e-522700.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Murata-Electronics/CSTCR7M99G53-R0?qs=Zd9RUO93%2Fo7cnwzsujIkpA%3D%3D)  | 0,27&euro; | 1x |
| CAN | MCP2551-I-SN | SOIC-8 |[Datasheet](http://ww1.microchip.com/downloads/en/devicedoc/21667d.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Microchip-Technology/MCP2551T-E-SN?qs=gZwDaUDMhIcQtLtB%252B7bOWQ%3D%3D) | 1,57&euro; | 1x |
| Regulador LDO | LM317KTTR | TO-263-3| [Datasheet](https://www.ti.com/general/docs/suppproductinfo.tsp?distId=26&gotoUrl=https://www.ti.com/lit/gpn/lm317) | [Mouser](https://www.mouser.es/ProductDetail/Texas-Instruments/LM317KTTR?qs=iSMark9AYDU6ASyyp8LD6g%3D%3D) | 0,74&euro; | 1x |
| Ferrita | BLM15AX100SND | SMD 0402 | [Datasheet](https://eu.mouser.com/datasheet/2/281/ENFA0018-1915754.pdf) | [Mouser](https://eu.mouser.com/ProductDetail/Murata-Electronics/BLM15AX601SN1D?qs=MY6wChARw2zrjX4xpWbUQA%3D%3D) |  0,94&euro; | 1x |
| Sensor RH-Temp | SHT1x | | [Datasheet](https://www.sparkfun.com/datasheets/Sensors/SHT1x_datasheet.pdf) | []() | | 1x |
| Rel&#233; | SR5-12V-200-1C  |- |[Datasheet](https://www.mouser.es/datasheet/2/670/sr5-2950657.pdf) | [Mouser](https://www.mouser.es/ProductDetail/CUI-Devices/SR5-12V-200-1C?qs=4ASt3YYao0WMNY1cu6cO0A%3D%3D)  | 1,17&euro; | 1x |
| Transistor | BC817-25-QR | SOT-23-3 | [Datasheet](https://www.mouser.es/datasheet/2/916/BC817_Q_SER-2498268.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Nexperia/BC817-25-QR?qs=e8oIoAS2J1TYx6o1G4RDyg%3D%3D) | 0,16&euro; | 1x |
| Polsador | EVP-BT7A4A000 | SMD | [Datasheet](https://www.mouser.es/datasheet/2/315/sw_lt_eng_6s_th-2889044.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Panasonic/EVP-BT7A4A000?qs=CiayqK2gdcK%2FK8JCTM%2FBCw%3D%3D) | 0,291&euro; | 3x |
| LED | 156120VS75000 green | SMD 1206 | [Datasheet](https://www.mouser.es/datasheet/2/445/156120VS75000-3085422.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Wurth-Elektronik/156120VS75000?qs=2kOmHSv6VfQAUFg5BeuEfQ%3D%3D) | 0,188&euro; | 1x |
| LED | 156120RS75000 red |SMD 1206  |[Datasheet](https://www.mouser.es/datasheet/2/445/156120RS75000-3085670.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Wurth-Elektronik/156120RS75000?qs=2kOmHSv6VfTlw4DhG%252BTIQw%3D%3D) | 0,188&euro; | 1x |
| Diode LDO | 1N4002T | THT axial |[Datasheet](https://www.diodes.com/assets/Datasheets/ds28002.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Diodes-Incorporated/1N4002-T?qs=rGAXPo9uwV21tVJRR%252BhxrQ%3D%3D) | 0,169&euro; | 3x |
| Diode transil | SMAJ15A-TR | SMD/SMT|[Datasheet](https://www.mouser.es/datasheet/2/389/smaj10ca-2956135.pdf) | [Mouser](https://www.mouser.es/ProductDetail/STMicroelectronics/SMAJ15A-TR?qs=fMNaVbI0QcP5ezTdgkCxZA%3D%3D) | 0,404&euro; | 1x |
| Capacitat 100nF | C0805C104M5RACTU | SMD 0805 |[Datasheet](https://www.mouser.es/datasheet/2/212/KEM_C1002_X7R_SMD-1102033.pdf) | [Mouser](https://www.mouser.es/ProductDetail/KEMET/C0805C104M5RACTU?qs=VOOUd%252Bza08qHu13WgNByHQ%3D%3D) | 0,022&euro; | 6x |
| Capacitat 10uF | MCASE32NSB5106MTNA01 | SMD 1210 |[Datasheet](https://www.mouser.es/datasheet/2/396/Taiyo_Yuden_1102023_MC_mlcc_all_e-3081584.pdf) | [Mouser](https://www.mouser.es/ProductDetail/TAIYO-YUDEN/MCASE32NSB5106MTNA01?qs=sGAEpiMZZMuMW9TJLBQkXugdD5SwFUVx3SlCD21BkBE%3D) | 0,30&euro; | 1x |
| Capacitat 1uF | 860020672005 | THT Radial 5mm |[Datasheet](https://www.mouser.es/datasheet/2/445/860020672005-3099424.pdf) | [Mouser](https://www.mouser.es/ProductDetail/TAIYO-YUDEN/MCASE32NSB5106MTNA01?qs=sGAEpiMZZMuMW9TJLBQkXugdD5SwFUVx3SlCD21BkBE%3D) | 0,084&euro; | 1x |
| Connectors | 10129378-910002BLF| tira pins poste 2.54 |[Datasheet](https://cdn.amphenol-cs.com/media/wysiwyg/files/documentation/datasheet/boardwiretoboard/bwb_econostik_254headers.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Amphenol-FCI/10129378-910002BLF?qs=0lQeLiL1qyYh8zFHsKDebQ%3D%3D) |0,18&euro; | x19 |
| Resist&#232;ncies | diverses | SMD 1206 | |  | | 11x |


## Historial de canvis

| Data | Autor     | Branch | Versi&#243; | Descripci&#243; |
| --- | --- | --- | --- | --- |
|  28/03/2023 | mlopez | Master | initial commit | Primera versi&#243; d'esquem&#224;tic i selecci&#243; de components |
|  30/03/2023 | dprades | P5 | v1 | Reselecci&#243; de components disponibles a mercat |
|  04/04/2023 | dprades | P5 | v2 | Esquem&#224;tic final i placement |
|  05/04/2023 | jcanals | P5 | v3 | Candidata a producci&#243; |
|  06/04/2023 | jcanals | P5 | v4 | Arreglat el Vadj del regulador.  |
|  20/04/2023 | dprades | P5 | v5 | Arreglats footprints uC, transil, switch i ferrita. |
|  20/04/2023 | dprades | P5 | v5.1 | Correccions menors format. |