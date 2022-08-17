## Note
nid: 1627974597782
model: Basic-d7a3e
tags: 05_uebung, 05_uebung_rs, checklater, klausur
markdown: false

### Front
Geben Sie die allgemeine <b>Formel</b> für die <b>durchschnittliche
Zugriffszeit</b> bei einer zweistufigen Cache-Hierarchie an, wobei
der Zguriff auf die nächste Ebene sequentiell stattfindet.

### Back
\[t_{a}=\underbrace{r_{H 1} * t_{L 1}}_{\text {Hit } L
1}+\underbrace{r_{M 1} *(\underbrace{r_{H 2} * t_{L 2}}_{\text {Hit
L2 }}+\underbrace{r_{M 2} * t_{\text {Mem }}}_{\text {Miss } L
1})}_{\text {Miss L2 }}\]
<div>
  \(r_H\) ist dabei die Hit-Rate, \(r_M\) die Miss-Rate, \(t_{L2}\)
  die Zugriffszeit auf den L2 Cache und \(t_{Mem}\) die
  Zugriffszeit auf auf den Hauptspeicher.
</div>
