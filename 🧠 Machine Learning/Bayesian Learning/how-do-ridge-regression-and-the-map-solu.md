## Note
nid: 1630656611676
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning, ultra
markdown: false

### Front
How do ridge regression and the MAP solution for linear regression relate?

### Back
<div>
  \(\begin{aligned} \boldsymbol{w}_{\mathrm{MAP}}
  &=\underset{\boldsymbol{w}}{\arg \max }
  \underbrace{\sum_{i}-\frac{1}{2
  \sigma^{2}}\left(y_{i}-\boldsymbol{w}^{T}
  \phi\left(\boldsymbol{x}_{i}\right)\right)^{2}}_{\text {Sum of
  squared errors }}-\underbrace{\frac{\lambda}{2}
  \boldsymbol{w}^{T} w}_{-\lambda /
  2\|w\|^{2}}+\underbrace{c\left(\sigma^{2}, \lambda\right)}_{\text
  {only interested in } \boldsymbol{w}} \\ &=\underset{w}{\arg
  \min } \sum_{i}\left(y_{i}-\boldsymbol{w}^{T}
  \phi\left(\boldsymbol{x}_{i}\right)\right)^{2}+\lambda \sigma^{2}
  \boldsymbol{w}^{T} \boldsymbol{w}-c\left(\sigma^{2},
  \lambda\right) \end{aligned}\)
</div>
<div>
  That is, if \(\lambda_{\text {ridge }}=\lambda \sigma^{2}\) the
  ridge solution and the MAP solution is equivalent.
</div>
