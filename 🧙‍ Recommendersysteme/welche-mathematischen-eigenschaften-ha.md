## Note
nid: 1593357427966
model: Basic-b122e-20a86
tags: 09_decision_trees
markdown: false

### Front
Welche (mathematischen) <b>Eigenschaften</b> hat die
<b>Entropie</b>?

### Back
<div>
  \(H(x, y) \leq H(x)+H(y)\) außer, wenn \(x\) und \(y\)
  unabhängig.
</div>
<div>
  Dann gilt \(H(x, y)=H(x)+H(y)\)
</div>
<div>
  Durchschnittsbildung erhöht die Entropie (Operationen der Form:
  \( p_{i}^{\prime}=\sum_{j} a_{i j} p_{j}\) mit \(\sum_{i} a_{i
  j}=\sum_{j} a_{i j}=1, \forall a_{i j} \geq 0\))
</div>
<div>
  \(x\) und \(y\) sind zwei Ereignisse (nicht unbedingt
  unabhängig).
</div>
<div>
  Für jeden Wert \(i\) den \(x\) annehmen kann, existiert bedingte
  Wahrscheinlichkeit \(p(y=j \mid x=i),\) dass \(y\) den Wert \(j\)
  hat:
</div>
<div>
  \[p(y=j \mid x=i)=\frac{p(i, j)}{\sum_{j} p(i, j)}\]
</div>
<div>
  Bedingte Entropie \(H(y \mid x)\) von \(y\) ist dann der
  Durchschnitt der Entropie von \(y\) für jeden Wert von \(x\)
  gewichtet mit der Wahrscheinlichkeit dieses \(x\) zu beobachten:
  \[H(y \mid x)=-\sum_{i, j} p(i, j) \log _{2} p(y=i \mid x=j)\]
  oder \[H(x, y)=H(x)+H(y \mid x)\]
</div>
