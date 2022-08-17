## Note
nid: 1610443073684
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie ist die <b>Criterion Function</b> beim Clustering definiert?

### Back
\[E=\sum_{i=1}^{k} \sum_{\vec{x} \in C_{i}} d\left(\vec{x},
\vec{m}_{i}\right),\]
<div>
  wobei \(k\) gegeben ist und \(E\) minimiert werden soll.
  \(\vec{m}_{i}\) ist der Cluster-Mittelpunkt. \(d\) die Distanz im
  metrischen Raum.
</div>
<div>
  <b>Intuition:</b>
</div>
<div>
  Man summiert die Distanz des Datenobjekts zu seinem jeweiligen
  Cluster-Mittelpunkt auf. Wenn ein Punkt in einem "falschen"
  Cluster ist, wird \(E\) größer, da der Summand \(d\) größer wird.
</div>
