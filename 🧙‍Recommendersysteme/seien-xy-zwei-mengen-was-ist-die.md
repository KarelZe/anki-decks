## Note
nid: 1588097030067
model: Basic-b122e
tags: 02_assoziationsregeln
markdown: false

### Front
Seien \(X,Y\) zwei Mengen.  Was ist die \(\operatorname{confidence}(X,Y)\) definiert?

### Back
<div>
  <b>Definition</b>
</div>
<div>
  confidence \((X,Y)=P(t \in T: X \subseteq t \wedge Y \subseteq
  t)\).
</div>
<div>
  <b>Alternative Definition mit bedingten Wahrscheinlichkeiten</b>
</div>
<div>
  \(\operatorname{confidence}(X, Y)=\frac{\operatorname{supp}(X
  \cup Y)}{\operatorname{supp}(X)}=\frac{P(X, Y)}{P(X)}=P(Y | X)\).
</div>
