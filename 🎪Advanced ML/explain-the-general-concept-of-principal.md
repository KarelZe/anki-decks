## Note
nid: 1621776666522
model: Basic-b122e
tags: 08_clustering
markdown: false

### Front
Explain the general concept of Principal Component Analysis.

### Back
<div>
  The first principal component of a set of features \(X_{1},
  X_{2}, \ldots, X_{P}\) is the normalized linear combination of
  the features \[P C A_{1}=\phi_{11} X_{1}+\phi_{21}
  X_{2}+\ldots+\phi_{P 1} X_{P}\] that has the largest variance. By
  normalized, we mean that \(\sum_{j=1}^{P} \phi_{j 1}^{2}=1\).
</div>
<div>
  We refer to the elements \(\phi_{11}, \phi_{21} \ldots, \phi_{P
  1}\) as the loadings of the firrst principal component; together,
  the loadings make up the principal component loading vector,
  \(\phi_{1}=\left(\phi_{11}, \phi_{21} \ldots, \phi_{P
  1}\right)^{T}\).
</div>
<div>
  <b>Visualization:</b>
</div>
<div><img src=
"paste-85be5b90109135d58d182111d7a9a53f3f0adc41.jpg"></div>
<div>
  First principal component direction in green and second in blue
  dashed line.
</div>
