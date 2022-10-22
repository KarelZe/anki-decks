# Note
```
guid: tJL:h$H,vs
notetype: Basic-d7a3e-4ce08
```

### Tags
```
03_vorlesung
```

## Front
How can one incorporate the idea of \(H_0\) and \(H_1\) to test for the significance of individual explanatory variables?

## Back
Formally, for each of the \(k\) explanatory variables, we test:
<div>
  \(H_{0}: \beta_{j}=0 \quad H_{1}: \beta_{j} \neq 0\)
</div>
<div>
  conditional on the other independent variables already included
  in the regression model.
</div>
<div>
  The appropriate test would be the t-test, given by:
</div>
<div>
  \(t_{j}=\frac{b_{j}-0}{s_{b_{j}}}\)
</div>
<div>
  t-test with \(n-k-1\) degrees of freedom, where \(b_j\) is the
  sample estimate of the \(j\)-th regression coefficient and
  \(s_{b_{j}}\) ist the standard error of the coefficient estimate.
</div>
