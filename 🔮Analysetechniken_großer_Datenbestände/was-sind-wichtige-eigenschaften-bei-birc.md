## Note
nid: 1632759134723
model: Basic-d7a3e
tags: 09_clustering_1, checklater
markdown: false

### Front
Was sind wichtige Eigenschaften bei BIRCH, die sich aus dem Tripel \(C F=(N, \vec{L F}, \vec{SS})\) bestimmen lassen?

### Back
<b>Centroid</b>:
<div>
  \(\overrightarrow{x_{0}}=\frac{\sum_{i=1}^{N}
  \overrightarrow{x_{i}}}{N}\)
</div>
<div>
  <b>Radius</b>:
</div>
<div>
  \(R=\left(\frac{\sum_{i=1}^{N}\left(\overrightarrow{x_{i}}-\overrightarrow{x_{0}}\right)^{2}}{N}\right)^{\frac{1}{2}}\)
</div>
<div>
  <b>Durchmesser</b>:
</div>
<div>
  \(D=\left(\frac{\sum_{i=1}^{N}
  \sum_{j=1}^{N}\left(\overrightarrow{x_{i}}-\overrightarrow{x_{j}}\right)^{2}}{N(N-1)}\right)^{\frac{1}{2}}\)
</div>
<div>
  <b>Durchschnittliche Inter-Cluster Distanz:</b>
</div>
<div>
  <div>
    \(D_{2}=\left(\frac{\sum_{i=1}^{N_{1}}
    \sum_{j=N_{1}+1}^{N_{1}+N_{2}}\left(\overrightarrow{x_{i}}-\overrightarrow{x_{j}}\right)^{2}}{N_{1}
    N_{2}}\right)^{\frac{1}{2}}\)
  </div>
</div>
