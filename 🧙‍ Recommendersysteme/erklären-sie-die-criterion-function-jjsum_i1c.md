# Note
```
guid: z1a8?Y#<0B
notetype: Basic-b122e-20a86
```

### Tags
```
10_Cluster_Modularity
```

## Front
Erklären Sie die Criterion Function \(J\):
<div>
  \[J=\sum_{i=1}^{c} \sum_{x_{j} \in
  D_{i}}\left\|x_{j}-m_{i}\right\|^{2}.\]
</div>

## Back
<div>
  Man iteriert also über jeden Punkt im Cluster und berechnet die
  Distanz zum Cluster-Mittelpunkt und wiederholt das Vorgehen für
  jedes Cluster. Das Ergebnis wird aufsummiert. Oberhalb wird die
  quadrierte Norm verwendet. Liegt ein Punkt im falschen Cluster
  wird die Summe entsprechend groß.
</div>
<div>
  Ziel ist es die Criterion-Function zu minimieren.
</div>
