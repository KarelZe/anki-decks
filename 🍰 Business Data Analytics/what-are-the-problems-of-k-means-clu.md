## Note
nid: 1655647327637
model: Basic-02d89
tags: 07_unsupervised_learning_bda
markdown: false

### Front
What are the <b>problems</b> of \(k\)-<b>means clustering</b>?

### Back
<ul>
  <li>\(k\) ist not fixed / a hyperparameter. -> The algorithm
  has has to be run for multiple different values of \(k\)
  <li>Algorithm is sensitive to outliers. -> Use medians instead
  of means.
  <li>Can't handle non-globular shapes. -> Use density-based
  clustering istead / increase \(k\)
</ul>
