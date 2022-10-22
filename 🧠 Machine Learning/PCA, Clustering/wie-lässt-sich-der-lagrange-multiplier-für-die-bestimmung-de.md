# Note
```
guid: dRE-P~Br`?
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::05_dim_reduction
```

## Front
<p>Wie lässt sich der Lagrange Multiplier für die Bestimmung der
<b>principal component directions</b> verwenden?

## Back
<p>Calculating the principal directions / components can be written
as:
<p>\(\boldsymbol{u}_{1}=\underset{\boldsymbol{u}}{\arg \max }
\boldsymbol{u}^{T} \boldsymbol{\Sigma} \boldsymbol{u} \quad\) s.t.
\(\boldsymbol{u}^{T} \boldsymbol{u}=1\)
<p>By applying Langranian optimization one gets the Langranian
given by:
<p>\(L(\boldsymbol{u}, \lambda)=\boldsymbol{u}^{T}
\boldsymbol{\Sigma} \boldsymbol{u}+\lambda\left(\boldsymbol{u}^{T}
\boldsymbol{u}-1\right)\)
<p>With an optimal solution for \(u\):
<p>\(\frac{\partial L(\boldsymbol{u}, \lambda)}{\partial
\boldsymbol{u}}=2 \boldsymbol{\Sigma} \boldsymbol{u}+2 \lambda
\boldsymbol{u} \stackrel{!}{=} \mathbf{0} \quad \Rightarrow
\boldsymbol{\Sigma} \boldsymbol{u}=\lambda \boldsymbol{u}\)
<p>Which is an Eigenvalue problem.
