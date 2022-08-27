## Note
nid: 1620499910971
model: Basic-d7a3e-4ce08
tags: adv_ml::08_clustering
markdown: false

### Front
When is a clustering optimal?

### Back
The idea behind \(k\)-means clustering is a good clustering, when
the within-cluster variation (WCV) is minimal.
\(\operatorname{WCV}(C_k)\) is the degree by which observations
differ from each other within a cluster. Hence we want to solve the
problem:
<div>
  \[\operatorname{ minimize }\left\{\sum_{k=1}^{K} W C
  V\left(C_{K}\right)\right\}\].
</div>
<div>
  For Euclidean distance:
</div>
<div>
  \[\operatorname{ minimize }\left\{\sum_{k=1}^{K}
  \frac{1}{\left|C_{K}\right|} \sum_{i, i^{\prime} \in C_{K}}
  \sum_{j=1}^{P}\left(x_{i j}-x_{i^{\prime} j}\right)^{2}\right\}\]
</div>
