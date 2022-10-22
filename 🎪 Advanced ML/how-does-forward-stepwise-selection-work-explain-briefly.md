# Note
```
guid: i=t?~cG#_n
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::06_lecture
```

## Front
How does <b>Forward Stepwise Selection</b> work? Explain briefly.

## Back
<div>
  <ol>
    <li>Let \(\mathcal{M}_{0}\) denote the null model, which
    contains no predictors.
    <li>For \(k=0, \cdots, p-1\): a. Consider all \(p-k\) models
    that augment the predictors in \(\mathcal{M}{k}\) with one
    additional predictor. <i>b.</i> Choose the best among these
    \(p-k\) models, and call it \(\mathcal{M}{k+1}\). Here best is
    defined as having smallest RSS or highest \(R^{2}\).
    <li>Select a single best model from among \(\mathcal{M}{0},
    \ldots, \mathcal{M}{p}\) using cross-validated prediction
    error, \(C_{p}\), (AIC), BIC, on adjusted \(R^{2}\).
  </ol>
</div>
