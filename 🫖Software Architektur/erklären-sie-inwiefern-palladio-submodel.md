## Note
nid: 1637341614496
model: Basic-d7a3e
tags: 04_Architectural_Reuse
markdown: false

### Front
Erklären Sie inwiefern Palladio Submodelle mehr Kontext binden? Wann im Softwareentwicklungszyklus stehen sie zur Verfügung?

### Back
<div><img src=
"paste-f6e5131034944a704c4ff94070401ed7e44c09f0.jpg"></div>Component
type can complete type (alle Schnittstellen) oder provided type
(angebotene Schnittstellen) sein.
<div>
  <div>
    Linke Spalte sagt in welchen Stufen im Entwicklungsprozess das
    Teilmodell auftaucht.
  </div>
  <div>
    Rechte Spalte zeigt nicht gebunden Kontext. Je weiter nach
    unten man geht, desto mehr Kontext wird gebunden. Man kann mehr
    Aussagen machen. Mittlere Spalte zeigt das Teil-Modell in PCM.
  </div>
</div>
<div>
  1:N-Beziehung, weil dieselbe Komponente kann in einen Assembly
  context gesetzt werden,... daraus verschiedene Laufzeitinstanzen
  erzeugt werden.
</div>
