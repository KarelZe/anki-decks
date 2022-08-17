## Note
nid: 1588096828115
model: Basic-b122e
tags: 02_assoziationsregeln
markdown: false

### Front
Sei \(T=\left(t_{1}, t_{2}, \ldots, t_{n}\right)\) eine Reihe von
Transaktionen mit \(t_{j} \subseteq I\).
<div>
  Wie definiert sich dann der <b>Support</b> für die Menge \(X\)?
</div>

### Back
<div>
  <b>Definition</b>
</div>\(\operatorname{support}(X)=\frac{|\{t \in T | X \subseteq
t\}|}{|T|}=\frac{\operatorname{count}(X)}{|T|}\)
<div>
  <b>Alternative Definition mit relativen Wahrscheinlichkeiten</b>
</div>
<div>
  \(\operatorname{support}(X)=P(t \in T: X \subseteq t)=P(X)\)
</div>
