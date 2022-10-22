# Note
```
guid: y`;F(yFR`E
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::06_lecture
```

## Front
How does <b>Best Subset Selection</b> work? Explain briefly.

## Back
1. Let \(\mathcal{M}_{0}\) denote the null model, which contains no predictors. This model simply predicts the sample mean for each observation.
2. For \(k=1,2, \ldots p\) :
    a. Fit all \(\left(\begin{array}{l}p \\ k\end{array}\right)\) models that contain exactly \(k\) predictors.
    b. Pick the best among these \(\left(\begin{array}{l}p \\ k\end{array}\right)\) models, and call it \(\mathcal{M}_{k}\). Here best is defined as having the smallest RSS, or equivalently largest \(R^{2}\).
3. Select a single best model from among \(\mathcal{M}_{0}, \ldots, \mathcal{M}_{p}\) using cross-validated prediction error, \(C_{p}\) (AIC), BIC, or adjusted \(R^{2}\)
