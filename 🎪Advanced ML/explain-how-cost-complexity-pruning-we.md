## Note
nid: 1621846479992
model: Basic-b122e
tags: 07_lecture_rf_dc
markdown: false

### Front
Explain how cost <b>complexity pruning</b> / <b>weakest link pruning</b> works.

### Back
We consider a sequence of trees indexed by a nonnegative tuning
parameter \(\alpha\). For each value of \(\alpha\) there
corresponds a subtree \[\sum_{m=1}^{|T|} \sum_{x_{i} \in
R_{m}}\left(y_{i}-\hat{y}_{R_{m}}\right)^{2}+\alpha|T|\]
<div>
  is as small as possible. Here \(|T|\) indicates the number of
  terminal nodes of the tree \(T, R_{m}\) is the rectangle (i.e.
  the subset of predictor space) corresponding to the \(m\)-th
  terminal node, and \(\hat{y}_{R_{m}}\) is the mean of the
  training observations in \(R_{m}\).
</div>
