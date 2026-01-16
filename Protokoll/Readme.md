## 19.09.2025
Aluschiene eloxiert -> mit Testschaltung1 probiert ob es möglich ist, dass auf Kontakt mit Hand Spannungsänderung erfolgt \
Bestellen THT-LED: https://at.rs-online.com/web/p/leds/2545723?gb=s \
Fragen:
- LED (SMD/ THT)
- LED (wie warm, zwei arten)
- Funktionalität (wischen (pi), berühren (schaltung))
- unten aus oben Helligkeit?
- U Profil?
- Abdeckung fürs Profil?
- wie mit Gehäuse verbinden

Funktionsweise:
- Sensor-Ausgang über Entprellschaltung an Clock-Eingang des Flip-Flops
- Flip-Flop-Ausgang steuert MOSFET
- MOSFET schaltet die LEDs

## 26.09.2025
Testschaltung1 mit LED und FLipFlop \
Zugentlastung vom HTL-Steyr Netzteil, Bohrung Pairleitner bis Freitag \\
Sicherungen: 5x20: \
https://at.rs-online.com/web/p/feinsicherungen/0563722?cm_mmc=AT-PPC-DS3A-_-google-_-DSA_AT_DE_Sicherungen+und+Leitungsschutzschalter_Index-_-Feinsicherungen%7C+Products-_-DYNAMIC+SEARCH+ADS&matchtype=&dsa-1654573426999&gclsrc=aw.ds&gad_source=1&gad_campaignid=17128883418&gbraid=0AAAAADkeWNNnLizClw80jrE_dvMhcoJ9_&gclid=CjwKCAjw89jGBhB0EiwA2o1On2qC14-NwMBfNiLWUObro9sYEJim8IOrced61eHoK35X3hhKKwx0OBoCeNgQAvD_BwE \
Sicherungshalter: \ 
https://at.rs-online.com/web/p/sicherungshalter/1769047?gb=s \
Ansteuerung 16 LEDs parallel der 

## 3.10.2025
- LED Print Fräsen und befästigen
- Fixierung an Schwanenhals (Pins an Drähte löten)
- Zugentlastung einbauen
- Schaltung mit CD4017B -> Durch Clock verschiedene Ausgänge schalten mit verschiedenen Stromstärken

### 10.10.2025
- Ausgang mit CD4017 funktioniert 6mA am Ausgang, mit MOSFET noch nicht
- Lösung für Sicherung finden
- U-Profil Abdeckung designen
  
Buchse: Schurter IEC-Steckverbinder C8 250 V, Gerade, Snap-In, Stecker, 2.5A, Steckverbinder - https://at.rs-online.com/web/p/iec-steckverbinder/1745470?gb=s  

## 07.11.2025
Trimmer: https://at.rs-online.com/web/p/trimmerpotentiometer/5222693 \
Kabelschuh: https://at.rs-online.com/web/p/flachsteckhulse/0534418



#### LEDSerie1.00
![Breadboard Aufbau 1](images/LEDSerie1.00.png)

#### Fußteil
https://www.ikea.com/at/de/p/blanda-blank-schuessel-edelstahl-30081467/
Zugentlastung vom HTL-Steyr Netzteil, Bohrung Pairleitner bis Freitag \

#### Sicherungshalter:
RS:
1) https://at.rs-online.com/web/p/sicherungshalter/2375259?cm_mmc=AT-PLA-DS3A-_-google-_-CSS_AT_DE_Pmax_Test-_--_-2375259&matchtype=&&gclsrc=aw.ds&gad_source=1&gad_campaignid=20298205821&gbraid=0AAAAADkeWNNVlQIv6luQNfW-9oEKOhcqK&gclid=Cj0KCQjw3aLHBhDTARIsAIRij582qfjgslcdfP3DjPyIMtyVTkf3t6P4wSuSAQbVUwuU7ELXbdX1ekcaAim_EALw_wcB
2) https://at.rs-online.com/web/p/sicherungshalter/2375260?cm_mmc=AT-PLA-DS3A-_-google-_-CSS_AT_DE_Pmax_Test-_--_-2375260&matchtype=&&gclsrc=aw.ds&gad_source=1&gad_campaignid=20298205821&gbraid=0AAAAADkeWNNVlQIv6luQNfW-9oEKOhcqK&gclid=CjwKCAjwup3HBhAAEiwA7euZusWiqs8Lys5GdcgIome2LbgBQE3lKgoIMlb5VDg9k_GD4PbvnzaJmxoCUQkQAvD_BwE

#### 3D-Teil:
1) https://www.thingiverse.com/thing:6588714/files
2) https://www.printables.com/model/1011753-halter-fur-fliegende-sicherung

#### U-Profil Abdeckung:
[U-Profil Abdeckung (STL)](./U-Profil_Abdeckung.stl)
[U-Profil Abdeckung (STL)](./U-Profil_Abdeckung_mit_Loch.stl)

#### LEDSerie1.00
![Breadboard Aufbau 1](images/LEDSerie1.00.png)

#### CD4017_1.00
![Breadboard Aufbau 1](images/CD4017_1.00.png)








## Testschaltung1
![Breadboard Aufbau 1](images/Testschaltung1.00.png) \
![Breadboard Aufbau 1](images/Testschaltung1.01.png)  \
![Breadboard Aufbau 1](images/Testschaltung1.02.png)  \

