## Note
nid: 1613744216774
model: Basic-b122e
tags: 07_vektorprozessoren, 12_Vektorverarbeitung, checklater, klausur, ultra
markdown: false

### Front
Welche Parallelitätsebenen bei Vektorrechnern unterscheidet man?

### Back
<ul>
  <li><b>Vektor-Pipeline-Parallelität:</b> durch die Stufenzahl der
  betrachteten Vektor-Pipeline gegeben <i>z. B. Vektorisierung
  inner Schleife</i>
  <li><b>Mehrere Vektor-Pipelines in einer Vektoreinheit:</b>
  Vorhandensein mehrer, meist funktional verschiedener
  Vektor-Pipelines in einer Vektoreinheit, durch Verkettung
  hintereinandergeschaltet <i>z. B. Verkettung von Befehlen oder
  Vektor-Verbundbefehlen Vector-Multiply-Add</i>
  <li><b>Vervielfachung der Pipelines:</b> Vektor-Pipeline
  vervielfachen, sodass bei Ausführung eines Vektorbefehls pro Takt
  nicht nur ein Paar von Operanden in eine Pipeline, sondern
  jeweils ein Operandenpaar in zwei oder mehr parallel arbeitende
  gleichartige Pipelines eingespeist werden. <i>z. B. Aufteilung
  innerer Schleife</i>
  <li><b>Mehrere Vektoreinheiten:</b> Arbeiten parallel zueinander
  nach Art eines speichergekoppelten Multiprozessors <i>z. B.
  Aufteilung äußere Schleife auf unterschiedliche
  Vektoreinheiten.</i>
</ul>
