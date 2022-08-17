## Note
nid: 1607857352368
model: Basic-d7a3e
tags: 05_dim_reduction, checklater, ultra
markdown: false

### Front
<p>Wie funktioniert die Berechnung der <b>first principal
direction</b> bei der <b>principal component analysis</b>? Wie der
zweiten?

### Back
<p>The first principal direction \(\boldsymbol{u}_{1}\) is the
direction along which the variance of the projected data is maximal
<p>\(\boldsymbol{u}_{1}=\underset{\boldsymbol{u}}{\arg \max }
\frac{1}{N} \sum_{i=1}^{N}(\boldsymbol{u}^{T}
\underbrace{\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)}_{\overline{\boldsymbol{x}}_{i}})^{2}
\quad\) s.t. \(\boldsymbol{u}^{T} \boldsymbol{u}=1\)
<p>Note that the directions have unit norm implied through the
constraint.
<p>The second principal direction maximizes the variance of the
data in the orthogonal complement of the first principal direction.
<p><img src="paste-4853cc17679d81491132eceda746d9c1e84eb049.jpg">
