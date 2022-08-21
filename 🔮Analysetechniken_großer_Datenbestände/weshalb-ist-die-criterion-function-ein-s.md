## Note
nid: 1610444300417
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1
markdown: false

### Front
Weshalb ist die <i>Criterion Function</i> ein schlechtes Maß, um
unterschiedliche Cluster-Algorithmen zu vergleichen?

### Back
<b>Hintergrund:</b>
<div>
  \[E=\sum_{i=1}^{k} \sum_{\vec{x} \in C_{i}} d\left(\vec{x},
  \vec{m}_{i}\right)\]
</div>
<div>
  Die Criterion Function (\(E\)) hängt stark ab von der Wahl des
  \(k\). Hat man sehr viele Cluster \(k\) z. B. gerade so viele wie
  Datenpunkte, dann ist \(E = 0\), obwohl wenig aussagekräftig.
</div>
<div>
  Criterion Function ist ungeignet, um Cluster mit
  unterschiedlicher Clusteranzahl zu vergleichen.
</div>
