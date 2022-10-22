# Note
```
guid: Eb_Xgvz[/b
notetype: Basic-9c783
```

### Tags
```
datenschutz::03_masse
```

## Front
Was ist die <b>Idee</b> der <b>Differential Privacy</b>?

## Back
Mein Datensatz soll möglichst wenige Auswirkungen haben f(DB) =
f(DB-{ich}) Angreifer nichts über mich lernen Pr[ Geheimnis(ich) |
E] = Pr[ Geheimnis(ich) ] Das Hinzufügen/Löschen eines beliebigen
Datensatzes \(X\) hat kleine Auswirkungen auf Ergebnis \(E\)
\(\frac{\operatorname{Pr}[f(D B)=E]}{\operatorname{Pr}[f(D
B+/-\{X\})=E]} \approx 1\) für alle \(D B, X\) und \(E\)
\(\mathrm{f}\) ist ein beliebiger Algorithmus, der Ergebnis \(E+\)
zufälliges Rauschen produziert <b>Beispiel:</b> \(E:=\) select
count \(\left({ }^*\right)+\) rand () from \(D B\) where Krankheit
\(=\) 'Impotenz'
