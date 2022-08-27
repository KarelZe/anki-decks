## Note
nid: 1653731871092
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
How does the <b>size</b> of the <b>coefficients</b> affect the
<b>ridge penalty</b>?

### Back
The Shrinkage penalty \(\lambda \sum_{j} \beta_{j}^{2}\) is small,
if coefficients are close to zero
<ul>
  <li>Shrinks the coefficients \(\beta_{1}, \ldots, \beta_{p}\)
  towards zero
  <li>\(\beta_{0}\) is not penalized \(\rightarrow\) corresponds to
  the sample mean
</ul>
