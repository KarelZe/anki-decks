# Note
```
guid: kgh_5dpT?o
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::09_lecture
```

## Front
Give the formulas for the <b>Least-Squares Support Vector
Regression with different intercepts for seniority classes</b>.

## Back
\[\begin{array}{r} \min J\left(w, b_{s}, u_{s
j}\right)=\frac{1}{2}\|w\|^{2}+\frac{1}{2} \sum_{s=1}^{S}
b_{s}^{2}+\frac{C}{2} \sum_{s=1}^{S} \sum_{j=1}^{n_{s}} u_{s j}^{2}
\\ \text { s.t. } \quad r_{i}=w^{T} \phi\left(X_{s
j}\right)+b_{s}+u_{s j}, \quad j=1, \ldots, n_{s}, s=1, \ldots, S
\end{array}\]
<div>
  One allows for different intercepts \(b_{s}\) for \(S\) different
  seniority classes. So we assume there is some kind of homogeneity
  within the seniority classes that can be represented by the
  different intercepts.
</div>
