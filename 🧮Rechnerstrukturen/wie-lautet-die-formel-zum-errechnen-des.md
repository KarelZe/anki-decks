## Note
nid: 1627818774542
model: Basic-d7a3e
tags: checklater, klausur
markdown: false

### Front
Wie lautet die Formel zum Errechnen des Gesamtwerts von Gruppen von Benchmarks? Welchen Vorteil hat diese Vorgehensweise gegenüber dem arithmetischen Mittel?

### Back
Man bildet das geometrische Mittel über die bezgl. der Referenzmaschine normalisierten Ausführungszeiten der einzelnen Programme \(\sqrt[n]{\prod_{i=1}^{n} \text { Execution time ratio }_{i}}\) wenn \(i\) ein Benchmark der Gruppe ist \(\left(\frac{1}{2} \mathrm{P}\right)\). Für das geometrische Mittel gilt: geometrisches Mittel \(\left(\frac{X_{i}}{Y_{i}}\right)=\frac{\text { geometrisches Mittel }\left(X_{i}\right)}{\text { geometrisches Mittel }\left(Y_{i}\right)}\) damit ergibt sich trotz der Relation zur Referenzmaschine ein konsistenter Wert beim Vergleich zweier Systeme. Dies wäre beim arithmetischen Mittel nicht gegeben. \(\left(\frac{1}{2} \mathrm{P}\right)\).
