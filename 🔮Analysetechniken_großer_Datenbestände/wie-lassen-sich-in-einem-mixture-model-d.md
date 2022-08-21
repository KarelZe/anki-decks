## Note
nid: 1633005976755
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Wie lassen sich in einem <b>Mixture Model</b> die Parameter
bestimmen, sofern die Klassenzugehörigkeit für \(x_{1}, x_{2},
\cdots, x_{{n}_{A}}\) aus Cluster \(A\) <b>bekannt</b> ist?

### Back
\(\mu_{A}=\frac{x_{1}+x_{2}+\ldots+x_{n_{A}}}{n_{A}}\)
<div>
  <div>
    \(\sigma_{A}^{2}=\frac{\left(x_{1}-\mu_{A}\right)^{2}+\left(x_{2}-\mu_{A}\right)^{2}+\ldots+\left(x_{n_{A}}-\mu_{A}\right)^{2}}{n_{A}-1}\)
  </div>
  <div>
    (Beachte man teilt durch \(n-1\) statt \(n\) um möglichst
    neutrale Schätzungen für die Varianz zu erhalten anstatt des
    maximum likelihoods)
  </div>
  <div>
    \(p_{A}=\frac{n_{A}}{n}\)
  </div>
</div>
