## Note
nid: 1616229754330
model: Basic-b122e
tags: 10_Cluster_Modularity
markdown: false

### Front
Erklären Sie einen Ansatz um die optimale Anzahl an Cluster \(c\) zu bestimmen.

### Back
\(H_{0}\): es sind \(c\) Cluster, da \((J(c))\) \(H_{1}\): es sind
\(c+1\) Cluster, da \((J(c+1))\)
<div>
  \[J(c)-J(c+1) \leq \varepsilon \text { und } P\left(H_{1}
  \text{wahr} \mid J(c)-J(c+1) \leq \varepsilon\right) \leq
  \theta,\]
</div>
<div>
  Wir akzeptieren \(H_{0}\), wenn: ... wenn also
  Wahrscheinlichkeit, dass \(H_{1}\) trotz dieser "geringen"
  Abnahme von \(J(c+1)\) verglichen mit \(J(c)\) stimmt, akzeptabel
  klein ist.
</div>
