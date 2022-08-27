## Note
nid: 1621068080933
model: Basic-d7a3e-4ce08
tags: adv_ml::06_lecture
markdown: false

### Front
How does <b>Backward Stepwise Selection</b> work? Explain briefly.

### Back
<div>
  <ol>
    <li>Let \(\mathcal{M}_{p}\) denote the <i>full</i> model, which
    contains all \(p\) predictors.
    <li>For \(k=p, p-1, \ldots, 1\) : a. Consider all \(k\) models
    that contain all but one of the predictors in
    \(\mathcal{M}{k}\), for a total of \(k-1\) predictors. b.
    Choose the <i>best</i> among these \(k\) models, and call it
    \(\mathcal{M}{k-1}\). Here <i>best</i> is defined as having
    smallest RSS or highest \(R^{2}\).
    <li>Select a single best model from among <em>\(\mathcal{M}{0},
    \ldots, \mathcal{M}\)</em> <em>using cross-validated prediction
    error, \(C_{p}\), (AIC), BIC, or adjusted \(R^{2}\).</em>
  </ol>
</div>
