# Note
```
guid: boS/]^eZKW
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
<p>Was ist die <b>Multinomial-Verteilung</b>?

## Back
<p>\(K\) different events: \(\quad C \in\{1, \ldots, K\}\).
<p>Directly specifies probabilities: \(p(C=k)=\mu_{k}, \quad
\mu_{k} \geq 0, \quad \sum_{k=1}^{K} \mu_{k}=1\).
<p>Or written with 1-hot-encoding (without an "if" clause) \[
p(c)=\prod_{k=1}^{K} \mu_{k}^{h_{c, k}} \]
<p>where \(h_{x}\) is a mask or a \(K\)-dimensional 1-hot encoding
vector e.g. \([0,0,1,0, \ldots]\).
<p>
