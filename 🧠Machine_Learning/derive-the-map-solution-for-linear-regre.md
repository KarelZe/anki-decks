## Note
nid: 1630656251829
model: Basic-d7a3e
tags: 09_bayesian_learning
markdown: false

### Front
Derive the <b>MAP solution</b> for <b>Linear Regression</b>.

### Back
Map solution is given by:<div>\(\boldsymbol{\theta}_{\mathrm{MAP}}=\underset{\theta}{\arg \max }(\log p(\mathcal{D} \mid \boldsymbol{\theta})+\log p(\boldsymbol{\theta}))\)
<div>
</div></div><div>Gaussian Likelihood:</div><div>\(p(\mathcal{D} \mid \boldsymbol{\theta})=p(\boldsymbol{Y} \mid \boldsymbol{X}, \boldsymbol{\theta})=\prod_{i} \mathcal{N}\left(y_{i} \mid f_{\boldsymbol{\theta}}\left(\boldsymbol{x}_{i}\right), \sigma^{2}\right)\)
</div><div>
</div><div>Gaussian Prior:</div><div>\(p(\boldsymbol{\theta})=\mathcal{N}\left(\boldsymbol{\theta} \mid \mathbf{0}, \lambda^{-1} \boldsymbol{I}\right)\)
</div><div>
</div><div>Objective:</div><div>\(\underset{\boldsymbol{\theta}}{\arg \max } \underbrace{\sum_{i}-\frac{1}{2 \sigma^{2}}\left(y_{i}-f_{\boldsymbol{\theta}}\left(\boldsymbol{x}_{i}\right)\right)^{2}}_{\text {Sum of squared errors }}-\underbrace{\frac{\lambda}{2} \boldsymbol{\theta}^{T} \boldsymbol{\theta}}_{-\lambda / 2\|\theta\|^{2}}+\underbrace{c\left(\sigma^{2}, \lambda\right)}_{\text {only interested in } \boldsymbol{\theta}}\)
</div>
