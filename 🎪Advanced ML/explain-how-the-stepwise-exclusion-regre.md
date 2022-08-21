## Note
nid: 1619951861432
model: Basic-b122e
tags: 03_vorlesung
markdown: false

### Front
Explain how the <b>stepwise exclusion regression method</b> works for <b>regression methods</b>.

### Back
At the beginning all explantory variables are included. One after
another the insignificant variables are elimated until all
insignificant explantory variables have been removed.
<div>
  All \(k\) explanatory variable are included in the regression
  first. Then we consider all variables for exclusion on a stepwise
  removal basis.
  <div>
    For each explanatory variable, we compute:
    <div>
      \[F=\frac{S S E_{k-1}-S S E_{k}}{\frac{S S E_{k-1}}{n-k}}\]
    </div>
    <div>
      to find the ones where \(F\) is insignificant.
    </div>
  </div>
</div>
