## Note
nid: 1639233177891
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Wie funktioniert die <b>risikoneutrale Bewertung</b> nach <b>Arrow-Debreu</b> rechnerisch?

### Back
Konstruktion von Arrow-Debreu Wertpapiere: <img src="98204465.png">
\(\left(\begin{array}{cc}1+r & 1+r \\ S u & S
d\end{array}\right)\left(\begin{array}{c}\Pi^{u} \\
\Pi^{d}\end{array}\right)=\left(\begin{array}{c}1 \\
S\end{array}\right)\) \(\Longrightarrow
\Pi^{u}=\frac{(1+r)-d}{(1+r)(u-d)}>0 \quad
\Pi^{d}=\frac{u-(1+r)}{(1+r)(u-d)}>0 \quad\) (Zustands- oder
Arrow-Debreu-Preise) Dann Ermittlung risikoneutraler
Wahrscheinlichkeiten: \[\begin{aligned} q &=\Pi^{u}(1+r)>0
\\ 1-q &=\Pi^{d}(1+r)>0 \\ \text { Gesetz des einen Preises
} \Longrightarrow P_{x}(0) &=\left(\begin{array}{c} \Pi^{u}
a^{u}+\Pi^{d} a^{d} \\ & =\left(q^{u}+r\right. \\ 1+r & (1-q)
\frac{a^{d}}{1+r} \end{array}\right) \end{aligned} \] Dann
Bestimmung des Optionswerts: \[\begin{aligned} \text { Gesetz des
einen Preises } \Longrightarrow P_{x}(0)
&=\left(\begin{array}{c} \Pi^{u} a^{u}+\Pi^{d} a^{d} \\ &
=\left(q^{u}+r\right. \\ 1+r & (1-q) \frac{a^{d}}{1+r}
\end{array}\right) \end{aligned} \] Dies ist ähnlich zu einem
Erwartungswert, den man noch abzinsen muss:
\[P_{x}(0)=E^{q}\left(\frac{P_{x}(1)}{1+r}\right)\] Der Optionswert
ist dann mit \(P_{x}(0)\) bestimmt.
