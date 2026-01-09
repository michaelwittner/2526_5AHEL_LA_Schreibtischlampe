## Anleitung Touch-Sensorik

Schaltplan:
<img width="1988" height="678" alt="grafik" src="https://github.com/user-attachments/assets/4ae7c7eb-9c29-4c83-9dcc-40e85c854999" />


Die Schaltung des NE555 Timer Bausteins ist folgendermaßen dimensioniert:

Mit R1 uns C1 lässt sich die Schaltzeit (t) einstellen.

$t = 1,1 \cdot R_1 \cdot C_1$

t=1,1 ∗R1 ∗C1

t=1,1 ∗220k ∗4,7µ

t=1,14s

Dies bedeutet, dass sich der Zustand (also die Helligkeit der Lampe) maximal
im 1,14s Takt einstellen lässt. Der 4017 Baustein schaltet bei jedem high Impuls am
CLK Eingang seine Ausgnänge (Q) durch. Bei Q4 Resetet er und rt beginnt wieder von
vorne. Hinter diesem IC wird die Helligkeit der LED's mittels Widerständen eingestellt.

Der Darlington Transistor Q3 Vertärkt nun die Ausgangsspannung und schaltet die LEDs durch.
