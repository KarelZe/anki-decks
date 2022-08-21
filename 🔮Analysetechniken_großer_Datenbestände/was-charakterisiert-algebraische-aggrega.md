## Note
nid: 1631720981207
model: Basic-d7a3e
tags: 02_statistik, checklater, ultra
markdown: false

### Front
Was charakterisiert <b>algebraische Aggregatsfunktionen</b>?

### Back
Es gibt Funktion \(G\), die M-Tupel liefert, und \(H\), so dass
\(F\left(\left\{X_{i,
j}\right\}\right)=H\left(\left\{G\left(\left\{X_{i, j} \mid i=1,
\ldots, I\right\}\right) \mid j=1, \ldots, J\right\}\right)\)
<div>
  \(M\) ist apriori bekannt, ebenso der Typ der Tupel.
  <div>
    <b>Intuition:</b>
  </div>
  <div>
    <b>Die Definition entspricht der distributiver Aggregate,
    jedoch hat man hier die Freiheit, in der inneren Klammer eine
    Funktion anzuwenden, die nicht die
    Ausgangsaggregatsfunktion</b> \(F\) ist. So könnte man z. B.
    \(AVG()\) folgendermaßen formalisieren:
  </div>
  <div>
    \(G:\) Menge von \(\mathbb{R} \rightarrow(\mathbb{R},
    \mathbb{N}), S \mapsto a:=\left(\sum_{x \in S} x,|S|\right)\)
    \(H:\) Menge von \((\mathbb{R}, \mathbb{N}) \rightarrow
    \mathbb{R}, A \mapsto \frac{\sum_{a \in A} a . f i r s
    t}{\sum_{a \in A} \text { a.second }}\)
  </div>
  <div>
    Zunächst werden alle Teilmengen der Augangsmenge auf Tupel,
    bestehend aus der Summe ihrer Elemente und ihrer Mächtigkeit,
    abgebildet. Damit erhält man die Menge aller dieser Tupel
    \(A\). Diese Menge wird daraufhin wieder gemäß der zweiten
    Zeile auf \(\mathbb{R}\) abgebildet.
  </div>
  <div>
    <b>Beispiel:</b> \(\operatorname{avg}()\)
  </div>
</div>
