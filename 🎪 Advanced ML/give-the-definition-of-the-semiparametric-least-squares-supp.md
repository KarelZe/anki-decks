# Note
```
guid: C!PnufGjGz
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::09_lecture
```

## Front
Give the definition of the Semiparametric <b>Least-Squares Support
Vector Regression</b>.

## Back
\[\begin{array}{l} \min J\left(w, b,
u_{i}\right)=\frac{1}{2}\|w\|^{2}+\frac{1}{2} \beta^{T}
\beta+\frac{1}{2} b^{2}+\frac{C}{2} \sum_{s=1}^{S}
\sum_{j=1}^{n_{k}} u_{s j}^{2} \\ \text { s.t. }
r_{i}=\mathbf{w}^{T} \phi\left(X_{i}\right)+\beta^{T} z_{s
j}+b+u_{s j}, \quad j=1, \ldots, n_{s}, s=1, \ldots, S,
\end{array}\]
<div>
  where the dummy variables for the seniority classes are \(z_{s
  i}\) and \(\beta\) is is a vector of fixed effects for the
  seniority of the respective group.
</div>
