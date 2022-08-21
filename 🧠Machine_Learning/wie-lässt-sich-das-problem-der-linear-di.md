## Note
nid: 1607857350814
model: Basic-d7a3e
tags: 05_dim_reduction, checklater
markdown: false

### Front
<p>Wie lässt sich das <b>Problem</b> der <b>Linear Dimensionality
Reduction</b> mathematisch formalisieren?

### Back
<p>Let \(\boldsymbol{x}_{i}\) be the \(i\)-th original data point \(\boldsymbol{x}_{i} \in \mathbb{R}^{D}\).</p><p>We try to find a low-dimensional representation of the \(i\)-th data point: \(\boldsymbol{z}_{i} \in \mathbb{R}^{M}\) with \(D>>M\).</p><p>This is equivalent to finding a mapping:</p><p>\(\boldsymbol{x}_{i} \rightarrow \boldsymbol{z}_{i}\)
</p><p>By restricting the mapping to be a linear function one gets:</p><p>\(\boldsymbol{z}_{i}=\boldsymbol{W} \boldsymbol{x}_{i}\), with \(\boldsymbol{W} \in \mathbb{R}^{M \times D}\)
</p>
