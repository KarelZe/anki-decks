# Note
```
guid: kqgoT8<waA
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
klausur
```

## Front
Wie lautet die Formel zum Errechnen des Gesamtwerts von Gruppen von Benchmarks? Welchen Vorteil hat diese Vorgehensweise gegenüber dem arithmetischen Mittel?

## Back
Man bildet das geometrische Mittel über die bezgl. der Referenzmaschine normalisierten Ausführungszeiten der einzelnen Programme \(\sqrt[n]{\prod_{i=1}^{n} \text { Execution time ratio }_{i}}\) wenn \(i\) ein Benchmark der Gruppe ist.


Für das geometrische Mittel gilt: geometrisches Mittel \(\left(\frac{X_{i}}{Y_{i}}\right)=\frac{\text { geometrisches Mittel }\left(X_{i}\right)}{\text { geometrisches Mittel }\left(Y_{i}\right)}\) damit ergibt sich trotz der Relation zur Referenzmaschine ein konsistenter Wert beim Vergleich zweier Systeme. Dies wäre beim arithmetischen Mittel nicht gegeben.
