Bauteilliste:

    C1	  4,7µ	    Capacitor_THT:C_Axial_L3.8mm_D2.6mm_P15.00mm_Horizontal
    C2	  100n	    Capacitor_THT:CP_Radial_Tantal_D4.5mm_P2.50mm
    C3	  100n	    Capacitor_THT:CP_Radial_Tantal_D4.5mm_P2.50mm
    D1	  1N4148	  Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal
    D2	  1N4148	  Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal
    D3	  1N4148	  Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal
    J1	  Versorgung	  TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal
    J2	  Lampenkopf	  TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-3-5.08_1x03_P5.08mm_Horizontal
    J5	  Messpunkte	  Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical
    Q1	  BC547	    Package_TO_SOT_THT:TO-92L_HandSolder
    Q2	  BC547	    Package_TO_SOT_THT:TO-92L_HandSolder
    Q3	  BD647	    Package_TO_SOT_THT:TO-220-3_Vertical
    R1	  1M	      Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal
    R2	  220k	    Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal
    R3	  4,7k	    Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal
    R5	  6k8	      Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal
    RV1	  10k	      Potentiometer_THT:Potentiometer_Bourns_3386P_Vertical
    RV2	  10M      	Potentiometer_THT:Potentiometer_ACP_CA9-V10_Vertical
    RV4	  10k	      Potentiometer_THT:Potentiometer_Bourns_3386P_Vertical
    U1	  NE555P	  Package_DIP:DIP-8_W7.62mm
    U2	  4017	    Package_DIP:DIP-16_W7.62mm
    U_Netzteil1	  Recom Netzteil	Libary:Recom_Netzteil_Footprint



## 19.09.2025
Aluschiene eloxiert -> mit Testschaltung1 probiert ob es möglich ist, dass auf Kontakt mit Hand Spannungsänderung erfolgt \
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


## Testschaltung1

![Breadboard Aufbau 1](images/Testschaltung1.00.png) \
![Breadboard Aufbau 1](images/Testschaltung1.01.png)  \
![Breadboard Aufbau 1](images/Testschaltung1.02.png)  \

## 26.09.2025
Testschaltung1 mit LED und FLipFlop \
Zugentlastung vom HTL-Steyr Netzteil, Bohrung Pairleitner bis Freitag \
Sicherungen: 5x20 https://at.rs-online.com/web/p/feinsicherungen/0563722?cm_mmc=AT-PPC-DS3A-_-google-_-DSA_AT_DE_Sicherungen+und+Leitungsschutzschalter_Index-_-Feinsicherungen%7C+Products-_-DYNAMIC+SEARCH+ADS&matchtype=&dsa-1654573426999&gclsrc=aw.ds&gad_source=1&gad_campaignid=17128883418&gbraid=0AAAAADkeWNNnLizClw80jrE_dvMhcoJ9_&gclid=CjwKCAjw89jGBhB0EiwA2o1On2qC14-NwMBfNiLWUObro9sYEJim8IOrced61eHoK35X3hhKKwx0OBoCeNgQAvD_BwE \
Sicherungshalter: https://at.rs-online.com/web/p/sicherungshalter/1769047?gb=s \

## 03.10.2025
Schaltung mit CD4017B -> Durch Clock verschiedene Ausgänge schalten

## 07.11.2025
Trimmer: https://at.rs-online.com/web/p/trimmerpotentiometer/5222693 \
Kabelschuh: https://at.rs-online.com/web/p/flachsteckhulse/0534418
