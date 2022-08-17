## Note
nid: 1629012907881
model: Basic-d7a3e
tags: 08_svm, checklater, formula_sheet
markdown: false

### Front
Explain how one can derive the dual form of the SVM. Do not consider slack variables.

### Back
First we have to introduce the <b>feature space</b> \(\phi (x_i)\)
by replacing \(x_i\).
<div>
  \(\begin{aligned} \operatorname{argmin}_{\mathbf{w}}
  &\|\mathbf{w}\|^{2}, \\ \text { s.t. } &
  y_{i}\left(\mathbf{w}^{T}
  \phi\left(\mathbf{x}_{i}\right)+b\right) \geq 1 \end{aligned}\)
</div>
<div>
  Define <b>Langraganian</b> as:
</div>
<div>
  \(\operatorname{argmin}_{\mathbf{w}}\|\mathbf{w}\|^{2}, \quad
  \text { s.t. } \quad y_{i}\left(\mathbf{w}^{T}
  \phi\left(\mathbf{x}_{i}\right)+b\right) \geq 1\)
</div>
<div>
  Compute the optimal \(w\) as:
</div>
<div>
  \(\begin{gathered} L(\boldsymbol{w},
  \boldsymbol{\lambda})=\frac{1}{2} \boldsymbol{w}^{T}
  \boldsymbol{w}-\sum_{i}
  \lambda_{i}\left(y_{i}\left(\boldsymbol{w}^{T}
  \phi\left(\boldsymbol{x}_{i}\right)+b\right)-1\right) \\
  \frac{\partial L}{\partial
  \boldsymbol{w}}=\boldsymbol{w}-\sum_{i} \lambda_{i} y_{i}
  \phi\left(x_{i}\right)=0 \\ \boldsymbol{w}^{*}=\sum_{i}
  \lambda_{i} y_{i} \phi\left(x_{i}\right) \end{gathered}\)
</div>
<div>
  Note that many of the \(\lambda\) will be 0. This is the case
  when the constraint is fullfilled. If it's not 0, \(\phi (x_i)\)
  is a support vector. Therefore, the optimal \(w\) is combination
  of the support variables.
</div>
<div>
  Find the optimal \(b\):
</div>
<div>
  \(L(\boldsymbol{w}, \boldsymbol{\lambda})=\frac{1}{2}
  \boldsymbol{w}^{T} \boldsymbol{w}-\sum_{i}
  \lambda_{i}\left(y_{i}\left(\boldsymbol{w}^{T}
  \phi\left(x_{i}\right)+b\right)-1\right)\)
</div>
<div>
  \(\frac{\partial L}{\partial b}=-\sum_{i} \lambda_{i} y_{i}
  \Rightarrow \sum_{i} \lambda_{i} y_{i}=0\)
</div>
<div>
  One gets no optimal solution for \(b\), but an additional
  constraint.
</div>
<div>
  Define <b>Langranian</b> as:
</div>
<div>
  \(L(\boldsymbol{w}, \boldsymbol{\lambda})=\frac{1}{2}
  \boldsymbol{w}^{T} \boldsymbol{w}-\sum_{i}
  \lambda_{i}\left(y_{i}\left(\boldsymbol{w}^{T}
  \phi\left(x_{i}\right)+b\right)-1\right), \quad
  \boldsymbol{w}^{*}=\sum_{i} \lambda_{i} y_{i}
  \phi\left(\boldsymbol{x}_{i}\right)\)
</div>
<div>
  Plug in \(w^{*}\).
</div>
<div>
  <b>Dual function:</b>
</div>
<div>
  \(\begin{aligned} g(\boldsymbol{\lambda})
  &=L\left(\boldsymbol{w}^{*}, \boldsymbol{\lambda}\right) \\
  &=\frac{1}{2} \underbrace{\sum_{i} \sum_{j} \lambda_{i}
  \lambda_{j} y_{i} y_{j} \phi\left(x_{i}\right)^{T}
  \phi\left(\boldsymbol{x}_{j}\right)}_{w^{* T} w^{*}}-\sum_{i}
  \lambda_{i} y_{i}(\underbrace{\sum_{j} \lambda_{j} y_{j}
  \phi\left(x_{j}\right)}_{w^{*}})^{T}
  \phi\left(x_{i}\right)+\sum_{i} \lambda_{i} \\ &=\sum_{i}
  \lambda_{i}-\frac{1}{2} \sum_{i} \sum_{j} \lambda_{i} \lambda_{j}
  y_{i} y_{j} \phi\left(\boldsymbol{x}_{i}\right)^{T}
  \boldsymbol{\phi}\left(\boldsymbol{x}_{j}\right) \end{aligned}\)
</div>
