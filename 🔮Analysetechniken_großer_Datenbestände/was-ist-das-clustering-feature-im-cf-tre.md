## Note
nid: 1611053847431
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1
markdown: false

### Front
Was ist das Clustering Feature im CF-Tree von BIRCH und welche Informationen umfasst es? Geben Sie die Formeln an.

### Back
<div>Information, die BIRCH zu jedem Cluster mitführt. Tripel aus \(CF =(N, \vec{LS}, \vec{SS})\). </div><div>
</div><div>\(N\) (Anzahl der Punkte im Cluster)</div><div>
</div><div>\(\vec{LS}=\sum_{i=1}^{N} \vec{X}_{i}\) (Linear sum)
</div><div>
</div><div><div>\(\vec{SS}=\sum_{i=1}^{N}\left({X}_{i}\right)^{2}\) (Squared Sum)</div></div>
<div>Man kann zwei Cluster zusammenfassen indem man die Tupel der Cluster-Features aufaddiert z. B. N+N, LS + LS, SS + SS aus Cluster 1 bzw. 2.
</div>
