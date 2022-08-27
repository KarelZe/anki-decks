## Note
nid: 1616224343671
model: Basic-b122e-20a86
tags: 10_Cluster_Modularity
markdown: false

### Front
Erklären Sie die <b>Bestandteile</b> der <b>Modularity-Formel</b>.<div>
</div>

\[
Q=\sum_{i=1}^{c}\left(e_{i i}-a_{i}^{2}\right)
\]

### Back
<ul><li>\(e_{i,i}\): Wahrscheinlichkeit einer Kante im Cluster \(C_i\) zu wählen bzw. der Anteil der Kanten im Cluster. Entspricht der tatsächlichen Dichte des Clusters  \(C_i\) verbindet.</li>
<li>\(a_{i}^2\): Erwarteter Anteil Kanten für einen zufälligen Graphen mit gleichem Knotengrad aller Knoten.</li></ul><div><b>Alternative Sicht:</b></div><div><ul><li>\(e_{i,j}\): Anteil Interclusterkanten \(C_i\) und \(C_j\)</li><li>\(e_{i,i}\): Anteil Intraclusterkanten \(C_i\) / "Dichte des Clusters"
</li></ul></div>
