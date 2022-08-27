## Note
nid: 1628051665129
model: Basic-d7a3e-4ce08
tags: 01_uebung, checklater, klausur, rs::01_uebung
markdown: false

### Front
Wie bestimmt man die Schaltwahrscheinlichkeit für ein
<b>UND-Gatter</b> mit <b>zwei Eingängen</b>?

### Back
<div>
  <b>Intuitition:</b>
</div>Ausgang ist 1, wenn beide Eingänge 1, sonst 0.
<div>
  4 Möglichkeiten (00,01,10,11), nur 11 ergibt 1 am Ausgang.
</div>
<div>
  <b>Signalwahrscheinlichkeit:</b>
</div>
<div>
  \(\mathbb{P}_{\text {Ausgang }}(1)=\frac{1}{4}, \quad
  \mathbb{P}_{\text {Ausgang }}(0)=\frac{3}{4}\)
</div>
<div>
  Einsetzen in allgemeine Formel für <b>Schaltwahrscheinlichkeit
  Gatter</b>:
</div>
<div>
  \(\mathbb{P}_{\text {Schalt }}=2 * \mathbb{P}(1)
  *(1-\mathbb{P}(1))\)
</div>
