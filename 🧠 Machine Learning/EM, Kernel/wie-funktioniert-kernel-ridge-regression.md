## Note
nid: 1610197687171
model: Basic-d7a3e-4ce08
tags: checklater, ml::07_kernel_methods, ultra
markdown: false

### Front
Wie funktioniert <b>kernel ridge regression</b>?

### Back
<div>
  Wie bekannt lautet die Lösung für \(\mathbf{w}^{*}\):
</div>
<div>
  \[\boldsymbol{w}_{\text {ridge }}^{*}=\underbrace{\left(\Phi^{T}
  \Phi+\lambda I\right)^{-1}}_{d \times d \text { matrix inversion
  }} \boldsymbol{\Phi}^{T} \boldsymbol{y}\]
</div>
<div>
  Bei unendlicher Dimension \(d\) ist Invertierung der Matrix nicht
  machbar.
</div>
<div>
  <b>Anwendung des kernel tricks:</b>
</div>
<div>
  D. h. Umschreiben der Lösung als Skalarprodukt der <i>feature
  spaces</i>. Man nutzt <i>searle set of identities</i>.
</div>
<div>
  Verwendung von Identität:
</div>
<div>
  \[(\boldsymbol{I}+\boldsymbol{\Phi}^{T}\boldsymbol{\Phi})^{-1}
  \boldsymbol{\Phi}^{T}=\boldsymbol{\Phi}^{T}(\boldsymbol{I}+\boldsymbol{\Phi}\boldsymbol{\Phi}^{T})^{-1}\]
</div>
<div>
  \[\begin{aligned} \boldsymbol{w}^{*}
  &=\underbrace{\left(\Phi^{T} \Phi+\lambda I\right)^{-1}}_{d
  \times d \text { matrix inversion }} \mathbf{\Phi}^{T}
  \boldsymbol{y}=\boldsymbol{\Phi}^{T}
  \underbrace{\left(\boldsymbol{\Phi} \Phi^{T}+\lambda
  I\right)^{-1}}_{N \times N \text { matrix inversion }}
  \boldsymbol{y}\\\end{aligned}\]
</div>
<div>
  Beachte \(N\) ist endlich, weil man nur endlich viele Samples
  haben kann.
</div>
<div>
  \[\boldsymbol{w}^{*} =\boldsymbol{\Phi}^{T}
  \underbrace{(\boldsymbol{K}+\lambda \boldsymbol{I})^{-1}
  \boldsymbol{y}}_{\boldsymbol{\alpha}}=\boldsymbol{\Phi}^{T}
  \boldsymbol{\alpha}\]
</div>
<div>
  Beachte \(\boldsymbol{w}^{*}\) kann selbst unendlich viele
  Dimensionen haben.
</div>
<div>
  Auswertung von \(\boldsymbol{w}^{*}\):
</div>
<div>
  \[f(\boldsymbol{x})=\phi(\boldsymbol{x})^{T}
  \boldsymbol{w}^{*}=\boldsymbol{\phi}(\boldsymbol{x})^{T}
  \boldsymbol{\Phi}^{T}
  \boldsymbol{\alpha}=\boldsymbol{k}(\boldsymbol{x})^{T}
  \boldsymbol{\alpha}=\sum_{i} \alpha_{i}
  k\left(\boldsymbol{x}_{i}, \boldsymbol{x}\right)\]
</div>
<div>
  <b>Auswirkungen</b>
</div>
<div>
  Man muss nicht mehr \(d \times d\) Matrix sondern \(N \times
  N-\)Matrix invertieren, was von Vorteil ist, wenn \(d > N\).
  \(\alpha\) ist aus \(\mathbb{R}^{N \times 1}\).
</div>
<div>
  Aber \(\boldsymbol{w}^{*}\) stammt immer noch aus \(\mathbb{R}^{d
  \times N}\) und kann unendlich dimensional sein und damit nicht
  repräsentiert werden.
</div>
