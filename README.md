# DELA EPROMMER II

![](https://codeberg.org/diwou/DELA-EPROMMER-II/raw/branch/main/Images/DELA%20EPROMMER%20II.jpg)

Nachbau des damals recht beliebten EPROM-Brenners „DELA EPROMMER II“. Aus einer alten, defekten Platine habe ich diesen Nachbau entworfen.

Im Originalzustand können mit diesem Programmieradapter die EPROM-Typen 2716 bis 27256 sowie die CMOS-Varianten davon gebrannt werden.

Mit einer entsprechenden Modifikation lassen sich sogar 27512-EPROMs programmieren.

Der DELA EPROMMER II war damals auch meine bevorzugte Möglichkeit, EPROMs zu brennen. Leider wurde das Original durch zu lange Lagerung im Keller zerstört. Aus nostalgischen Gründen habe ich den Programmieradapter noch einmal nachgebaut.

# Aufbau

Die Platine ist vollständig mit bedrahteten Bauteilen bestückt, wie es damals üblich war. Besondere Anforderungen gibt es keine. Alle Teile sind handelsüblich und in jedem gut sortierten Elektronikladen leicht erhältlich.

Auch für Einsteiger sollte der Aufbau und das Löten dieser Platine kein Problem darstellen.

Die Platine von oben betrachtet:

![](https://codeberg.org/diwou/DELA-EPROMMER-II/raw/branch/main/Images/DELA%20EPROMMER%20II%202.jpg)

# Stückliste

Hier die Liste der benötigten Bauteile. Die genannten Hersteller dienen als Beispiel – selbstverständlich können auch kompatible Teile anderer Hersteller verwendet werden.

| Menge | Bezeichnung | Hersteller                  | Herstellernummer              | Beschreibung |
|-------|-------------|-----------------------------|-------------------------------|--------------|
| 1     | D4          | NTE Electronics             | 1N752A                        | Zenerdiode 5,6 V, 0,5 W, 5 %, DO-35 |
| 4     | D7–D10      | ON Semiconductor / Fairchild| 1N4002                        | Standarddiode 100 V, 1 A, DO-41 |
| 3     | D1, D5, D6  | NXP Semiconductors          | 1N4148                        | Schalt-Diode 1N4148, Ammo-Pack |
| 1     | D3          | ON Semiconductor / Fairchild| 1N5236B                       | Zenerdiode 7,5 V, 0,5 W, DO-35 |
| 1     | D2          | ON Semiconductor / Fairchild| 1N5237B                       | Zenerdiode 8,2 V, 0,5 W, DO-35 |
| 1     | U1          | 3M                          | 228-4817-00-0602J             | ZIF-Sockel, DIP-28, vergoldet |
| 1     | LED1        | Würth Elektronik            | 151033RS03000                 | LED 3 mm, rot, 2600 mcd, 621 nm |
| 6     | Q1–Q4, Q6, Q7 | Multicomp                  | BC237B                        | NPN-Transistor, 45 V, 200 MHz, 100 mA |
| 1     | Q5          | ON Semiconductor / Fairchild| BC558BTA                      | PNP-Transistor, -30 V, 150 MHz, -100 mA |
| 2     | U2, U3      | Texas Instruments           | CD4040BE                      | 12-Bit Binärzähler, DIP-16 |
| 2     | R9, R11     | Yageo                       | CFR-25JB-52-1K                | Widerstand 1 kΩ, 0,25 W, 5 %, axial |
| 9     | R2–R8, R10, R12 | Yageo                    | CFR-25JB-52-10K               | Widerstand 10 kΩ, 0,25 W, 5 %, axial |
| 1     | R1          | Yageo                       | CFR-25JB-52-680K              | Widerstand 680 kΩ, 0,25 W, 5 %, axial |
| 1     | CP3         | Panasonic                   | ECA1EHG101                    | Elko 100 µF, 25 V |
| 2     | CP2, CP4    | Panasonic                   | ECA-1HHG471                   | Elko 470 µF, 50 V |
| 1     | CP5         | Panasonic                   | ECA-1VHG471                   | Elko 470 µF, 35 V |
| 1     | U6          | STMicroelectronics          | L7805CV                       | Spannungsregler 5 V, TO-220 |
| 1     | CP1         | RND Components              | RND 150EHR100M16B             | Elko 10 µF, 16 V, 20 % |
| 1     | U4          | Texas Instruments           | SN74LS06N                     | Inverter Open Collector, 6-fach, DIP-14 |
| 1     | U5          | Texas Instruments           | SN74LS373N                    | Latch 8-fach, 3-state, DIP-20 |

# Lizenz

Der Inhalt dieses Repositories, mit Ausnahme der Verzeichnisse „Docs“ und „Software“, steht unter folgender Lizenz:

- **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**  
Der vollständige Lizenztext befindet sich in der Datei [LICENSE.CC-NC-BY-SA-4.0](https://codeberg.org/diwou/DELA-EPROMMER-II/raw/branch/main/LICENSE.CC-NC-BY-SA)  
Eine Kopie ist außerdem hier verfügbar: https://creativecommons.org/licenses/by-nc-sa/4.0/
