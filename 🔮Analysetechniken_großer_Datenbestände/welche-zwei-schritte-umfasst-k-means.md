## Note
nid: 1632492482629
model: Basic-d7a3e
tags: 09_clustering_1
markdown: false

### Front
Welche zwei Schritte umfasst \(k\)-Means?

### Back
<ol><li>Bestimme \(k\) Medoide \(p_{1}, \ldots, p_{k}\) (Seeds) für einen gegebenen Datenbestand (Initialisierung)</li><li>Ordne jeden Datenpunkt dem nächsten Medoid zu; minimiere die Criterion function: \[
E= \sum_{i=1}^{k} \sum_{j=1}^{N_{i}} d\left(p_{i,} x_{j}^{i}\right)
\]</li></ol>
