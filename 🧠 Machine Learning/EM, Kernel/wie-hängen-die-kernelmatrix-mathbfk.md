## Note
nid: 1610194264987
model: Basic-d7a3e-4ce08
tags: checklater, ml::07_kernel_methods
markdown: false

### Front
Wie hängen die Kernelmatrix \(\mathbf{K}\), der Kernel \(\kappa\) und die Abbildung \(\mathbf{\Phi}_X\) zusammen?

### Back
<div>
  Feature matrix:
</div>Sei
\(\boldsymbol{\Phi}_{X}=\left[\begin{array}{c}\phi\left(\boldsymbol{x}_{1}\right)^{T}
\\ \vdots \\
\phi\left(\boldsymbol{x}_{N}\right)^{T}\end{array}\right] \in
\mathbb{R}^{N \times d}\) dann gelten nachfolgende Identitäten für
die Matrix. \(d\) ist Dimension von der Samples. Können \(\infty\)
sein.
<div>
  <div>
    Kernel matrix: \(\quad K=\Phi_{X} \Phi_{X}^{T}\)
  </div>
  <div>
    Check: \([\boldsymbol{K}]_{i
    j}=\phi\left(\boldsymbol{x}_{i}\right)^{T}
    \boldsymbol{\phi}\left(\boldsymbol{x}_{j}\right)=k\left(\boldsymbol{x}_{i},
    \boldsymbol{x}_{j}\right)\)
  </div>
  <div>
    Kernel vector: \(\quad
    k\left(x^{*}\right)=\left[\begin{array}{c}k\left(x_{1},
    x^{*}\right) \\ \vdots \\ k\left(x_{N},
    x^{*}\right)\end{array}\right]=\left[\begin{array}{c}\phi\left(x_{1}\right)^{T}
    \phi\left(x^{*}\right) \\ \vdots \\ \phi\left(x_{N}\right)^{T}
    \phi\left(x^{*}\right)\end{array}\right]=\Phi_{X}
    \phi\left(x^{*}\right)\) \(x^{*}\) is an unseen point, that is
    compared against every point in the data set.
  </div>
</div>
