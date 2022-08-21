## Note
nid: 1611055508752
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Erklären Sie den <b>CF-Tree</b>?

### Back
<ul>
  <li>CF-Tree ist ein höhenbalancierter Baum
  <li>Jeder Knoten des Baums entspricht <b>einem</b> Cluster.
  <li>Man hat Enthaltenbeziehung, wenn Knoten zu Cluster A in
  Knoten zu Cluster B enthalten ist, ist A in B enthalten.
  <li>Blatt ist eine Menge von Clustering Features (s. g.
  <b>Elementar-Cluster)</b>
  <li>Innere Knoten enthalten Einträge der Form \(\left(C F_{i},
  child_{i}\right)\)(\(CF_i\) ist Clustering Feature von
  \(child_i\))
  <li>Clustering Features sind ein Tipel \(CF = (N, \vec{LS},
  \vec{SS})\), woraus sich Eigenschaften der Cluster berechnen
  lassen. Bei inneren Knoten ergeben sich die CFs aus den CFs
  seiner Kinder.
  <li>Die Größe des Baums ist relativ unabhängig von der Anzahl der
  Datenobjekte. → Baum verwaltet nicht die Datenobjekte selbst,
  sondern die Clustering Features. Ausnahmen sind ggf. Ausreiser.
</ul>
<div>
  <b>Visualisierung:</b>
</div>
<div><img src="1fHBbXb356JiVtxwEJagnIQ.jpeg"></div>
<div>
  Ermittlung Cluster-Features:
</div>
<div><img src=
"paste-45ff212f3b41e490185184cb63857c22726cd7d1.jpg"></div>
<div><img src=
"paste-7a87dc1bb63573bc8e7598ad60e5c2bc5e7571a4.png"></div>
