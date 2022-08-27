## Note
nid: 1620908489151
model: Basic-d7a3e-4ce08
tags: adv_ml::09_lecture
markdown: false

### Front
Give the definition of the <b>Least-Squares Support Vector
Regression</b> Model

### Back
\[\begin{aligned} \min J\left(w, b, u_{i}\right)
=\frac{1}{2}\|w\|^{2}+\frac{C}{2} \sum_{i=1}^{N} u_{i}^{2} \\ \text
{ s.t. } \quad r_{i}=w^{T} \phi\left(X_{i}\right)+b+u_{i}, \quad
i=1, \ldots, N, \end{aligned}\]
<div>
  where \(w\) is the weight vector of the independent variables
  while \(b\) is the intercept. The regularization parameter \(C\)
  scales the error terms \(u_{i}^{2}\) and \(\phi(X)\) denotes the
  kernel function for the feature mapping.
</div>
