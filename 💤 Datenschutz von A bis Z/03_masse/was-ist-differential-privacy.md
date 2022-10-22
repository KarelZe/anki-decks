# Note
```
guid: b~~`c:]>;^
notetype: Basic-9c783
```

### Tags
```
datenschutz::03_masse
ultra
```

## Front
Was ist <b>Differential Privacy</b>?

## Back
Wenn <b>Hinzufügen/Entfernen einer Person</b> die <b>Verteilung
eines Anfrageergebnisses</b> nicht signifikant ändert, bleibt
Privatheit gewahrt. Es gilt: Verteilung aller Attribute ist
bekannt, d.h. \(\operatorname{Pr}[E]\) :
Eintrittswahrscheinlichkeit für Ereignis \(E\) ist bekannt, X:
Datensatz einer Person, Zwei Datenbestände \({DB}_1\) und \({DB}_2:
D B_2=D B_1 \cup\{X\}\) Eine Funktion \(K\) genügt der
\(\epsilon\)-differential privacy, wenn für alle \({DB}_1\) und
\(D_2\) und alle \(S \subseteq\) Wertebereich \((K)\) gilt:
\[\operatorname{Pr}\left[K\left(D B_1\right) \in S\right] \leq
e^\epsilon * \operatorname{Pr}\left[K\left(D B_2\right) \in
S\right]\]Beim Abfragen, addiere auf Ergebnis einen zufälligen
(Laplace verteilten) Wert mit Wahrscheinlichkeitsdichte
\(\mathrm{p}\), Schwerpunkt \(x\) proportional zu: \[p(x) \propto
e^{(-|x| / \epsilon)}\] <b>Visualisierung: <img src="paste-ed5967021c4059e71384c64a5f790cd4878cc414.jpg"> Beispiel:</b>
<img src="paste-156d1882a0e1729bebe2b2700d1c2cb820c9e037.jpg">
