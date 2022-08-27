## Note
nid: 1653730664281
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
Why does <b>Ridge Regression</b> improve upon <b>LS</b>?

### Back
<ul>
  <li>Shrinkage of coefficients reduces flexiblity. Leading to an
  decrease in variance but an increase in bias.
  <li>Ridge regression performs well in cases where the
  LS-coefficients have high variance, e.g. \(n \approx p\)
  <li>Computationally advanced compared to best subset selection
  (\(2^p\) possible models)
  <li>It's unlikely that coefficients are fully 0.
</ul>
