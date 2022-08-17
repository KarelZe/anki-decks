## Note
nid: 1621085309166
model: Basic-b122e
tags: 06_lecture
markdown: false

### Front
How can Cross-Validation help with estimating \(\lambda\) for
<b>Ridge Regression</b> and <b>LASSO?</b>

### Back
We require a method selecting a value for the tuning parameter
\(\lambda\) or equivalently, the value of the constraint \(s\).
<div>
  With Cross-Validation we choose a grid of \(\lambda\) values, and
  compute the cross-validation error rate for each value of
  \(\lambda\).
</div>
<div>
  One selects the tuning parameter value, where the
  cross-validation error is smallest.
</div>
