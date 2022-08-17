## Note
nid: 1629437314493
model: Basic-d7a3e
tags: 01_linear_regression, checklater
markdown: false

### Front
Give the definition of <b>generalized linear regression models / linear basis function models</b>.

### Back
\(f(\boldsymbol{x})=\boldsymbol{\phi}(\boldsymbol{x})^{T}
\boldsymbol{w},\)
<div>
  where \(\phi(\boldsymbol{x})\) is a vector valued function of the
  input vector \(\boldsymbol{x}\). So \(\boldsymbol{x}\) gets
  transformed by this function. That is, \(\boldsymbol{y}\) is no
  longer linearily dependent on \(\boldsymbol{x}\).
</div>
<div>
  <b>Example:</b>
</div>
<div>
  \[ f(\boldsymbol{x})=\boldsymbol{\phi}(\boldsymbol{x})^{T}
  \boldsymbol{w} \] where \[ \boldsymbol{w}=\left[\begin{array}{l}
  w_{0} \\ w_{1} \\ w_{2} \\ w_{3} \end{array}\right], \quad
  \phi(\boldsymbol{x})=\left[\begin{array}{c} 1 \\ x \\ x^{2} \\
  x^{3} \end{array}\right] \]
</div>
<div><img src=
"paste-6fd93cf457a811c4f11916b6f814266eb94ad44d.jpg"></div>
