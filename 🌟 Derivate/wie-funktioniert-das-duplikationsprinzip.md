## Note
nid: 1639230508017
model: Basic-02d89-e0e22
tags: 05_bewertung, derivate::05_bewertung
markdown: false

### Front
Wie funktioniert das <b>Duplikationsprinzip </b>rechnerisch?

### Back
Konstruktion des Duplikationsportefeuilles:
\[\left(\begin{array}{l}
a^{u} \\
a^{d}
\end{array}\right)=\Delta\left(\begin{array}{c}
S u \\
S d
\end{array}\right)+B\left(\begin{array}{c}
1+r \\
1+r
\end{array}\right)
\]

\(\Delta\) ist dabei die Anzahl der riskanten Wertpapiere. Bestimmt sich aus Veränderung der Optionswerte im Verhältnis zu der Veränderung der Basiswerte.
\(B\) bestimmt die Anzahl der risikolosen Wertpapiere.

Dann bestimmen von \(\Delta\) und \(B\):
\(\Delta=\frac{a^{u}-a^{d}}{S u-S d}\)
\(B=\frac{u a^{d}-d a^{u}}{(u-d)(1+r)}\)

Dann ermitteln von \(P_x(0)\) mit Gesetz des einen Preises.
\(\begin{aligned} P_{x}(0) &=\Delta S+B \\ &=\left(\frac{1+r-d}{u-d} a^{u}+\frac{u-(1+r)}{u-d} a^{d}\right) \frac{1}{1+r} \end{aligned}\)

<b>Hinweis:</b>
\(B\) muss man sich nicht unbedingt merken, da man Auszahlungsprofil der Option auch durch Strategie mit \(\Delta\) Aktien long und Kredit nachbilden kann. Kredit gleicht dann aus, sodass sich Auszahlungsprofil der Option ergibt. Wert in \(t=0\) ist dann der Preis der Option.
