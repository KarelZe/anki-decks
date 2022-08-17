## Note
nid: 1653735566809
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
What is the variance inflation factor?

### Back
R-Squared of a predictor, if it is regressed by all other predictors.

\(\operatorname{VIF}\left(\hat{\beta}_{j}\right)=\frac{1}{1-R_{X_{j} / X_{-j}}^{2}}\)

Rule of thumb:
VIF of 5 or 10 is problematic.
