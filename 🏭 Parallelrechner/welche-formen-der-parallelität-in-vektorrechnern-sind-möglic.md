# Note
```
guid: Lf2TwO?Avf
notetype: Basic-b122e-20a86
```

### Tags
```
2_6_parallelrechner
```

## Front
Welche Formen der Parallelität in Vektorrechnern sind möglich?

## Back
<ul>
  <li><b>Vektor-Pipeline-Parallelität:</b> durch die Stufenzahl der
  betrachteten Vektor-Pipeline gegeben
  <li><b>Mehrere Vektor-Pipelines in einer Vektoreinheit:</b>
  Vorhandensein mehrer, meist funktional verschiedener
  Vektor-Pipelines in einer Vektoreinheit, durch Verkettung
  hintereinandergeschaltet
  <li><b>Vervielfachung der Pipelines:</b> Vektor-Pipeline
  vervielfachen, sodass bei Ausführung eines Vektorbefehls pro Takt
  nicht nur ein Paar von Operanden in eine Pipeline, sondern
  jeweils ein Operandenpaar in zwei oder mehr parallel arbeitende
  gleichartige Pipelines eingespeist werden.
  <li><b>Mehrere Vektoreinheiten:</b> Arbeiten parallel zueinander
  nach Art eines speichergekoppelten Multiprozessors
</ul>
