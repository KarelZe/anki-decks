## Note
nid: 1607857353338
model: Basic-d7a3e
tags: 05_dim_reduction, checklater, formula_sheet
markdown: false

### Front
<p>Wie lässt sich der Lagrange Multiplier für die Bestimmung der
<b>principal component directions</b> verwenden?

### Back
<p>Calculating the principal directions / components can be written as:</p><p>\(\boldsymbol{u}_{1}=\underset{\boldsymbol{u}}{\arg \max } \boldsymbol{u}^{T} \boldsymbol{\Sigma} \boldsymbol{u} \quad\) s.t. \(\boldsymbol{u}^{T} \boldsymbol{u}=1\)
</p><p>By applying Langranian optimization one gets the Langranian given by:</p><p>\(L(\boldsymbol{u}, \lambda)=\boldsymbol{u}^{T} \boldsymbol{\Sigma} \boldsymbol{u}+\lambda\left(\boldsymbol{u}^{T} \boldsymbol{u}-1\right)\)
</p><p>With an optimal solution for \(u\):</p><p>\(\frac{\partial L(\boldsymbol{u}, \lambda)}{\partial \boldsymbol{u}}=2 \boldsymbol{\Sigma} \boldsymbol{u}+2 \lambda \boldsymbol{u} \stackrel{!}{=} \mathbf{0} \quad \Rightarrow \boldsymbol{\Sigma} \boldsymbol{u}=\lambda \boldsymbol{u}\)
</p><p>Which is an Eigenvalue problem.</p>
