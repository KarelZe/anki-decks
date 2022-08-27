## Note
nid: 1616232441143
model: Basic-b122e-20a86
tags: 10_Cluster_Modularity
markdown: false

### Front
Was ist die Idee von <b>Core Groups Graph Clustering</b>?

### Back
<ul>
  <li>Identifizieren von Knoten, deren Zuordnung zu Clustern nicht
  stabil ist: Mehrere Durchläufe (Stichprobe der Größe \(k\) ) des
  RG (oder eines beliebigen Algorithmus) durchgeführt
  <li>Aufgrund des nicht-deterministischen Verhaltens: Jeweils
  Berechnung leicht unterschiedlicher (jeweils für sich gute)
  Partitionen
  <li>Es existieren aus \(k\) verschiedenen Durchläufen von
  Clusteralgorithmen eine Menge\(S=\{ P_{1}, \cdots, P_{k}\} \)
  Partitionen.
  <li>Wenn nun ein Knotenpaar \(v, w \in V\) in allen Partitionen
  in \(S\) im selben Cluster liegen, so sind diese Knoten Teil
  einer Core Group. \[ \begin{aligned} \forall i=1 . . k: \forall
  v, w \in V:\left(c_{P_{i}}(v)=c_{p_{i}}(w)\right) \Rightarrow
  c_{\hat{p}}(v)=c_{\hat{P}}(w) \\ \exists i=1 . . k: \forall v, w
  \in V:\left(c_{P_{i}}(v) \neq c_{p_{i}}(w)\right) \Rightarrow
  c_{\hat{p}}(v) \neq c_{\hat{p}}(w) \end{aligned} \]
</ul>
<div>
  <b>Skizze:</b>
</div>
<div><img src=
"Untitled-9c480b2e05d08a818b65ae16416793968efb1c94.png"></div>
