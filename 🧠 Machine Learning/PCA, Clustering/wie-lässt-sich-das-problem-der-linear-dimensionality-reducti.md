# Note
```
guid: dU}#g-2TGS
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::05_dim_reduction
```

## Front
<p>Wie lässt sich das <b>Problem</b> der <b>Linear Dimensionality
Reduction</b> mathematisch formalisieren?

## Back
<p>Let \(\boldsymbol{x}_{i}\) be the \(i\)-th original data point
\(\boldsymbol{x}_{i} \in \mathbb{R}^{D}\).
<p>We try to find a low-dimensional representation of the \(i\)-th
data point: \(\boldsymbol{z}_{i} \in \mathbb{R}^{M}\) with
\(D>>M\).
<p>This is equivalent to finding a mapping:
<p>\(\boldsymbol{x}_{i} \rightarrow \boldsymbol{z}_{i}\)
<p>By restricting the mapping to be a linear function one gets:
<p>\(\boldsymbol{z}_{i}=\boldsymbol{W} \boldsymbol{x}_{i}\), with
\(\boldsymbol{W} \in \mathbb{R}^{M \times D}\)
