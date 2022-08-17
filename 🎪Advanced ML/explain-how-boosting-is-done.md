## Note
nid: 1621848113717
model: Basic-b122e
tags: 07_lecture_rf_dc
markdown: false

### Front
Explain how <b>Boosting</b> is done.

### Back
Assume we seek to fit a gradient boosting model to the
\(\left(X_{1}, y_{1}\right),\left(X_{2}, y_{2}\right),
\ldots,\left(X_{n}, y_{n}\right)\), where \(X_{i}\) are the
explanatory variables for the \(i^{\text {th }}\) sample and
\(y_{i}\) is its dependent variable.
<div>
  In the first step, using gradient boosting we fit a base learner
  \(f_{0}(X)\) for modeling. We define the corresponding prediction
  residuals for first regression tree \(e_{i
  0}=y_{i}-f_{0}\left(X_{i}\right)\) for \(i=1,2, \ldots, n\) . In
  the next step, a regression tree \(f_{1}\left(X_{i}\right)\) to
  \(\left(X_{1}, e_{10}\right),\left(X_{2}, e_{20}\right),
  \ldots,\left(X_{n}, e_{n 0}\right)\) is fit, and a recovery rate
  prediction will be equal to \(f_{0}\left(X_{i}\right)+e_{i 1}\).
  <div>
    Here \(e_{i 1}\) is the corresponding predicted residuals from
    \(f_{1}\left(X_{i}\right)\). The gradient boosting estimation
    after \(B\) iterations is defined as:
    \[\widehat{y}_{i}=f_{0}\left(X_{i}\right)+\sum_{b=1}^{B} e_{i
    b}\]
  </div>
</div>
