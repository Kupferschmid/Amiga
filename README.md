# Amiga 2K Front Panel
Pimp Your Amiga!

Das Amiga 2K Front Panel erweitert den Amiga 2000 mit einer Blende für den 5,25" Schacht. Damit kann ein externer Tastaturumschalter von [7-bit A234](https://retro.7-bit.pl/?lang=en&go=projekty&name=SUM234) intern benutzt werden und von außen komplett bedient werden in dem eine USB-Tastatur / USB-Funk-Dongle in den oberen linken Schacht gesteckt wird. Durch Drücken des danebenliegenden Tasters leuchtet die Taste und signalisiert, dass die USB-Tatstatur aktiv ist. erneutes drücken der Taste schält wieder auf die angesteckte Original-Tastatur um. Der Taster daneben aktiviert den Programmiermodus des 7-bit A234.


Der USB-Schacht in der Mitte dient zum externen erreichen des RaspberryPi-USB-Ports der auf dem  [PiStorm 2K](https://github.com/captain-amygdala/pistorm) sitzt, damit kann mann leicht Dateien dem Amiga OS zugänglich zu machen.


Der Taster in der Mitte ist mit einem [HDMI-Switch](https://www.amazon.de/dp/B07H7JCCKM) verbunden und leuchtet auf, sobald der HDMI-Ausgang des PiStrorms auf den [RGBtoHDMI](https://github.com/LinuxJedi/AmigaRGBtoHDMI/tree/main/Amiga2000CPLDSlot) Ausgang umgeschaltet wird, damit kann komfortabel ein HDMI-Monitor genutzt werden sowohl für die klassische HIRES-Auflösung von Spielen aber auch über den PiStorm kann bis zu 4K mit der Workbench gearbeitet werden.

Der untere Schacht führt die micro SD-Card des RaspberryPi nach außen mithilfe eines [Verlängerungkabels](https://www.amazon.de/gp/product/B09MTJ17ZX)
Der Platz links im Panel ist für den späteren einbau eines [GoTek Systems USB Drive](https://de.aliexpress.com/item/1005005882655063.html)

## BOM
| | | | |
|-|-|-|-|
|Name|Bauteil|Kommentar|Footprint|
|U2|MAX4736EUB+ |MAX4736EUB_|SOP50P490X110-10N|
|U1|CD4013BM96G4 |CD4013BM96G4|SOIC |
|S2, S3|TL1240GQ1JCLR |TL1240GQ|SW_TL1240GQ|
| | | | |
|R7|3.9kΩ, 0603 SMD|R3k9|0603 |
|R6|1.8kΩ, 0603 SMD|R1k8|0603 |
|R5|1.0MΩ, 0603 SMD|R1M|0603 |
|R2|120.0Ω, 0603 SMD|R120|0603 |
|R1, R3, R4|ILSB0603ER100K |R100k|0603 |
|J6|B6B-XH-A(LF)(SN) |B6B-XH-A|JST_B6B-XH-A|
|J5|BG030-04-A-0450-0300-N-G |Tast+Led_RGB2HDMI|PinHeader_1x04_P2.54mm_Vertical|
|J4|BG030-04-A-0450-0300-N-G |Tast+LED_Keyboard|PinHeader_1x04_P2.54mm_Vertical|
|J2|B5B-XH-A(LF)(SN) |7-bit_A234_Adapter|JST_B5B-XH-A|
|D1, D2|1N4148W |1N4148W|SOD123 |
|C2|1.0nF, 0603 SMD|C1n|0603 |
|C1, C3|100.0nF, 0603 SMD|C100nF|0603 |
|Q1, Q2 |BC847C,235 |BC847W|SOT323 |
|S1|TL1240BQ1JCLR|TL1240BQ|SW_TL1240GQ|

![fusion360 Frontpanel Back](https://github.com/Kupferschmid/Amiga/blob/main/images/fusion360-Frontpanel_Front.png)
![fusion360 Frontpanel Back](https://github.com/Kupferschmid/Amiga/blob/main/images/fusion360-Frontpanel_Back.png)
![](https://github.com/Kupferschmid/Amiga/blob/main/images/Schaltplan%20Amiga2K_Front_Panel.png)
![Amiga2K Front Panel Platine](https://github.com/Kupferschmid/Amiga/blob/main/images/Amiga2K-Front-Panel-Platine.png)
![Amiga 2K Front Panel Platine](https://github.com/Kupferschmid/Amiga/blob/main/images/A234_installed_in%20Panel.jpg)
![SUM A234](https://github.com/Kupferschmid/Amiga/blob/main/images/SUM%20A234.png)
![PiStorm2K für Amiga 2000 Retro Buddys PiStorm2K](https://www.retrobuddys.com/wp-content/uploads/2024/01/retro-jan-3-scaled.jpg)
![Ugreen HDMI Switch](https://github.com/Kupferschmid/Amiga/blob/main/images/Ugreen%20hdmi-Switch.jpg)
