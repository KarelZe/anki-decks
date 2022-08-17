## Note
nid: 1629438829869
model: Basic-d7a3e
tags: 01_linear_regression, checklater
markdown: false

### Front
Explain how one can find the optimal \(\boldsymbol{w}\), that
minimizes SSE.
<div>
  \(\boldsymbol{w}^{*}=\operatorname{argmin}_{\boldsymbol{w}}
  \mathrm{SSE}\)
</div>

### Back
One tries to find \(\frac{\partial \mathrm{SSE}}{\partial
\boldsymbol{w}}=\mathbf{0}^{T}\).
<div>
  \(\begin{aligned} \operatorname{SSE}(\boldsymbol{w})
  &=(\boldsymbol{y}-\boldsymbol{X}
  \boldsymbol{w})^{T}(\boldsymbol{y}-\boldsymbol{X} \boldsymbol{w})
  \\ &=\boldsymbol{w}^{T} \boldsymbol{X}^{T} \boldsymbol{X}
  \boldsymbol{w}-\boldsymbol{y}^{T} \boldsymbol{X}
  \boldsymbol{w}-\boldsymbol{w}^{T} \boldsymbol{X}^{T}
  \boldsymbol{y}+\boldsymbol{y}^{T} \boldsymbol{y} \\
  &=\boldsymbol{w}^{T} \boldsymbol{X}^{T} \boldsymbol{X}
  \boldsymbol{w}-2 \boldsymbol{y}^{T} \boldsymbol{X}
  \boldsymbol{w}+\boldsymbol{y}^{T} \boldsymbol{y} \end{aligned}\)
</div>
<div>
  Take the derivative w.r.t. \(\boldsymbol{w}\).
</div>
<div>
  \(\begin{aligned} \nabla_{\boldsymbol{w}}
  \operatorname{SSE}(\boldsymbol{w})&=\frac{\partial}{\partial
  \boldsymbol{w}}\left\{\boldsymbol{w}^{T} \boldsymbol{X}^{T}
  \boldsymbol{X} \boldsymbol{w}-2 \boldsymbol{y}^{T} \boldsymbol{X}
  \boldsymbol{w}+\boldsymbol{y}^{T} \boldsymbol{y}\right\}\\ &=
  \boldsymbol{X} \boldsymbol{X}^{T} \boldsymbol{X} \boldsymbol{w} -
  \boldsymbol{X} \boldsymbol{X}^{T} \boldsymbol{y} = 0
  \end{aligned}\)
</div>
<div>
  Setting the gradient to 0 yields:
</div>
<div>
  \(\boldsymbol{w}^{*}=\left(\boldsymbol{X}^{T}
  \boldsymbol{X}\right)^{-1} \boldsymbol{X}^{T} \boldsymbol{y}\)
</div>
