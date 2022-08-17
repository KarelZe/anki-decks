## Note
nid: 1633007500999
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Wie muss ein <b>Mixture Model</b> erweitert werden für <b>mehr
als</b> ein <b>Attribut</b>.

### Back
<div>
  <b>Unabhängige Attribute:</b>
</div>
<div>
  Kovarianzen 0.
</div>
<div>
  Man kann dann schreiben:
</div>
<div>
  \(\operatorname{Pr}[A \mid x, y]=\frac{\operatorname{Pr}[x,y\mid
  A] \cdot \operatorname{Pr}[A]}{\operatorname{Pr}[x,
  y]}=\frac{\operatorname{Pr}[x \mid A] \cdot \operatorname{Pr}[y
  \mid A] \cdot \operatorname{Pr}[A]}{\operatorname{Pr}[x, y]}\),
  wobei \(A\) und \(B\) jeweils Clusterings sind.
</div>
<div>
  Man muss damit \(2n\) Parameter bei Mittelwert und
  Standardabweichung pro Dimension bei \(n\) Attributen berechnen.
</div>
<div>
  <b>Korrelierte Atttribute:</b>
</div>
<div>
  Annahme einer bivariaten Normalverteilung. Sind Attribute
  korreliert, so benötigt man noch Kovarianzmatrix. Kovarianzmatrix
  ist symmetrisch. Es genügt deshalb obere Dreiecksmatrix zu
  berechnen. Damit ergeben sich bei \(n\) kovarianten Attributen:
</div>
<div>
  \(n+\frac{n(n-1)}{2}\), d. h. \(n\) Mittelwert + \(n \times n\)
  Kovarianzmatrix.
</div>
